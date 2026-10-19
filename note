<?php
$notes = ["Mohamed" => 14, "Sami" => 9, "Amel" => 17,
"Yassine" => 8, "Ines" => 12];
foreach ($notes as $name => $note) {
    echo $name . " : " 
    . $note . "<br>";
}
$moyenne =array_sum($notes) / count($notes);
echo "La moyenne est : " 
. $moyenne ."<br>";
$admis =array_filter(
    $notes,
    fn($note) => $note >= 10
);
print_r($admis);
function moyenne($notes) {
    return array_sum($notes) / count($notes);
}
echo "La moyenne est : " . moyenne($notes) . "<br>";
