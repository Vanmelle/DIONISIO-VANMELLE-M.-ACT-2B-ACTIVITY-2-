<?php


/*
Basic Information 
Nickname: Van
Name: Vanmelle M. Dionisio
Age: 21
Address: Balungao, Calumpit, Bulacan
Hobbies: Reading, Coding, Playing Basketball
Dream Job: Software Engineer
Course: Associate in Computer Technology
School: Bulacan Polytechnic College
*/

$me = array(

    "name" => "Vanmelle M. Dionisio",
    "age" => 21,
    "address" => "Balungao, Calumpit, Bulacan",
    "hobbies" => "Reading, Coding, Playing Basketball",
    "dream_job" => "Software Engineer",
    "course" => "Associate in Computer Technology",
    "school" => "Bulacan Polytechnic College"
);

echo "My Personal Information\n";
echo "Name: " . $me["name"] . "\n";
echo "Age: " . $me["age"] . "\n";
echo "Address: " . $me["address"] . "\n";
echo "Hobbies: " . $me["hobbies"] . "\n";
echo "Dream Job: " . $me["dream_job"] . "\n";
echo "Course: " . $me["course"] . "\n";
echo "School: " . $me["school"] . "\n\n";

print "I am " . $me["name"] . ", a " . $me["course"] . " student of " . $me["school"] . ".";

?>
