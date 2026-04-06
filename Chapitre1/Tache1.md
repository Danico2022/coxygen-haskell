-- HC1 Task1
-- Définition de la fonction

-- Multiplie un nombre par 2.
double x = x * 2

-- Augmente un nombre de 1.
increment a = a + 1

-- Composition de fonctions
doubleThenIncrement = increment.double 

-- Programme principal pour tester la fonction
main :: IO ()
main = do
   print(double 7)
   print(increment 7)
   print(doubleThenIncrement 2)
