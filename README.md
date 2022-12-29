# Normalizer-PHP
We can normalize string PHP to use the function in class Normalizer

#How to use this?
## 1- You instance Normalizer class
## 2- You call 'normalize' function

#Example
$normalizer = new Normalizer();
$string = "élie, comment ça va?"
$result = $normalizer->normalize($string);

echo $result;

This is returne a string "elie, comment ca va?"
