# UProjectileMovementComponent\*

En komponent för att förflytta ett objekt som en projektil.

``` cpp title="AProjectile.h"
UProjectileMovementComponent* ProjectileMovement;
```

``` cpp title="AProjectile.cpp"
ProjectileMovement = 
  CreateDefaultSubobject<UProjectileMovementComponent>(TEXT("Projectile Movement"));
```

## InitialSpeed

Hastigheten projektilen ska ha från början.

```cpp
ProjectileMovement->InitialSpeed = 3000.0f;
```

## MaxSpeed

Projektilens maxhastighet.

```cpp
ProjectileMovement->MaxSpeed = 3000.0f;
```

## bShouldBounce

Ifall projektilen ska studsa.

```cpp
ProjectileMovement->bShouldBounce = true;
```
