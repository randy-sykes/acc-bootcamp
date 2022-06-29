cd ~/Desktop
mkdir drinks
mkdir drinks/Smoothies drinks/FrozenDrinks drinks/IcedSpecialtyDrinks
mv drinks/Smoothies drinks/PowerSmoothies
smoothies='drinks/PowerSmoothies'
touch $smoothies/PeachAndBlueberry.txt $smoothies/GreenPassion.txt $smoothies/Superfruit.txt
frozen='drinks/FrozenDrinks'
touch $frozen/WatermelonStrawberryLemonade.html $frozen/Caramel.html $frozen/Mocha.html
speciality='drinks/IcedSpecialtyDrinks'
touch $speciality/CaramelLatte.css $speciality/ChaiTeaLatte.css $speciality/CaffeMocha.css $speciality/CaffeLatte.css
rm $speciality/CaffeLatte.css
