# UPropertyErrorDemoTmp

This project demonstrates what seems to be an error in the property system.

Given a class with a TArray<FTransfrom>, if a blueprint subclass is created for the class and a bool is added to it, the values stored for persistent instances of the blueprint subclass are destroyed.
Values for persistent instances of the class (not blueprint subclasses) spawned from the C++ definition are not lost.
