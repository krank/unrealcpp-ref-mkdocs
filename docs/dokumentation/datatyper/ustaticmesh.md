# UStaticMesh

En uppsättning statiska 3D-polygoner. Kan roteras, flyttas och skalas men enskilda vertexar kan inte animeras.

``` cpp title="PlayerPawn.h"
UPROPERTY(EditAnywhere)
UStaticMesh* Mesh;
```

Själva UStaticMesh-objektet skapas generellt i ett 3D-program, importeras till Unreal Engine och kopplas till en UStaticMesh-variabel via Unreal-editorn.
