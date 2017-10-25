# Pig Latin Unit Tests

## Installation
Clone into a directory of your choice.

`git clone https://github.com/bnelo12/Pig-Latin-Unit-Tester.git`

## Use
Simply run:

`./test_convert_pig_latin /PATH/TO/convert_pig_latin.c /PATH/TO/convert_pig_latin.s /PATH/TO/Mars.jar`

You can omit the last two arguments if you just want to test your C code.

## Tests
This will test your C code and MIPS to a series of inputs as follows:

```
check "Testing test test!" "Enter input: output: Estingtay esttay esttay!"
check "...!!!..." "Enter input: output: ...!!!..."
check ".. HELLO .. allo .. a .." "Enter input: output: .. ELLOHAY .. alloay .. aay .."
check "A..capital..Letter" "Enter input: output: AAY..apitalcay..Etterlay"
check "THESE-WORDS Have-hyphens..and..-Punctu-ation" "Enter input: output: ESE-WORDSTHAY Ave-hyphenshay..anday..-Unctu-ationpay"
check "Hello-" "Enter input: output: Ellohay-"
check "COMPOUND-WORDS" "Enter input: output: OMPOUND-WORDSCAY"
check "simple" "Enter input: output: implesay"
check "" "Enter input: output:"
check "ths hs n vwls" "Enter input: output: thsay hsay nay vwlsay"
check "A" "Enter input: output: AAY"
check "a" "Enter input: output: aay"
check "Aye-aye captain, Say SIMPLE thanks! ty." "Enter input: output: Aye-ayeay aptaincay, Aysay IMPLESAY anksthay! tyay."
check "hi mom this is a lot o wordsss lawwlll yu see what im talkin abuuut lolzter Yuuuu-puuu kikukuk eeeoak nmnjabj oeokeleleoelk okwpoaw kwpoaw dud WOOO SUPErMAN FLYING BROOMS A,nd some. pi;nctuattttt Like mieal Mooore Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis naque penatibus THISWORDISFIFTYCHARSLONGIFYOUDOITONCELIKEICECUBEYH et magnis dis parturient montes, nascetur ridiculus mus. Donec qthiswordisfiftycharslongifyoudoitoncelikeicecubeyh arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. orem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies Thiswordisfiftycharslongifyoudoitoncelikeoicecubeyh" "Enter input: output: ihay ommay isthay isay aay otlay oay ordsssway awwllllay uyay eesay atwhay imay alkintay abuuutay olzterlay Uuuu-puuuyay ikukukkay eeeoakay abjnmnjay oeokeleleoelkay okwpoaway oawkwpay udday OOOWAY Upermansay INGFLYAY OOMSBRAY AAY,nday omesay. ipay;uatttttnctay Ikelay iealmay Oooremay Oremlay ipsumay olorday itsay ametay, onsectetuercay adipiscingay elitay. Aeneanay ommodocay igulalay egetay olorday. Aeneanay assamay. Umcay ociissay aquenay enatibuspay ISWORDISFIFTYCHARSLONGIFYOUDOITONCELIKEICECUBEYHTHAY etay agnismay isday arturientpay ontesmay, asceturnay idiculusray usmay. Onecday iswordisfiftycharslongifyoudoitoncelikeicecubeyhqthay arcuay. Inay enimay ustojay, oncusrhay utay, imperdietay aay, enenatisvay itaevay, ustojay. Ullamnay ictumday elisfay euay edepay ollismay etiumpray. Integeray incidunttay. Ascray apibusday. Ivamusvay elementumay empersay isinay. Aeneanay ulputatevay eleifenday ellustay. Aeneanay eolay igulalay, orttitorpay euay, onsequatcay itaevay, eleifenday acay, enimay. oremay anteay, apibusday inay, iverravay uisqay, eugiatfay aay, ellustay. Asellusphay iverravay ullanay utay etusmay ariusvay aoreetlay. Uisqueqay utrumray. Aeneanay imperdietay. Etiamay ultriciesay Iswordisfiftycharslongifyoudoitoncelikeoicecubeyhthay"

```

If a test fails the diff between the expected outputs and the program outputs is displayed.

Please report any errors.
