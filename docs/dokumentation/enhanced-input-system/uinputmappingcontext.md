# UInputMappingContext

Ett objekt som knyter ihop [UInputActions](uinputaction/README.md) med knapptryck från spelaren.

``` cpp title="PlayerPawn.h"
UPROPERTY(EditAnywhere, Category="Input")
UInputMappingContext* MappingContext;
```

Själva Input Mapping Context-objektet skapas i regel i Unreal-editorn, och länkas in till en UInputMappingContext-variabel i klassen.
