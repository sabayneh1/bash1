!/bash/sh
read -p 'Enter first number following by second number and arithmetic operator' n1 n2 art
if [[ $n1 = "" || $n2 = "" || $art = "" ]] ;
then
        echo "This script required 3 arguments"
exit 1
fi;
if [ "$art" = "/" ] ;
then
        echo  $n1 divided by $n2 is $(($n1/$n2))
elif [ "$art" = "*" ] ;
then
        echo  $n1 multiply by $n2 is $(($n1*$n2))
elif [ "$art" = "-" ] ;
then
        echo  $n1 subtract $n2 is $(($n1-$n2))
elif [ "$art" = "+" ] ;
then
        echo  $n1 plus $n2 is $(($n1+$n2))
elif [ "$art" = "%" ] ;
then
       echo  The mode of $n1 and $n2 is $(($n1%$n2))
        echo "Error you have either entered non number character or you have provided the right arithmetic operator, Please try again"   
fi;

