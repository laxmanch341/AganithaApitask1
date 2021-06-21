# Aganitha-Api-task1
## spoken English to written English
##### This REST API based service convert a paragraph of spoken english to written english. For example, "two dollars" should be converted to $2. Abbreviations spoken as "H T M L" or "Triple A" should be written as "HTML" and "AAA" respectively.
#installation of required libraries

run the following command

pip install spoken2written

# usage
import spoken2written
from spoken2written import TextTranslator 
## input
test="two dollars"

TextTranslator(test)
## output
print(test)
$2
