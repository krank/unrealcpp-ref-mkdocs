# UTextRenderComponent

En komponent som visar en text som ett objekt i spelvärlden (till skillnad från en text-widget, som visar en text i UI:t). Ärver från [USceneComponent](uscenecomponent.md).

## SetText()

Ändrar vilken text som visas av komponenten; tar emot en [FText](../datatyper/README.md#strings) som parameter.

``` cpp
CountdownText->SetText(FText::FromString("GO!"));
```

## SetWorldSize()

Ändrar textens storlek i världen. Tar emot en [float](../datatyper/README.md#grundlaggande) som parameter.

```cpp
CountdownText->SetWorldSize(150.0f);
```

## SetHorizontalAlignment()

Ändrar centreringen för texten. Alternativen är EHTA\_Left, EHTA\_Right och EHTA\_Center.

``` cpp
CountdownText->SetHorizontalAlignment(EHTA_Center);
```
