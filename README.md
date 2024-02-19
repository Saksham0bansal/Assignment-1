<?php
$TP=5500;
if ($TP >5000){
    $DP=$TP-($TP*0.1);
    echo"discounted price is".$DP;
}
else {
    echo"Totalprice is".$TP;
}
