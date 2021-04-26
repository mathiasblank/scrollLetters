
# scrollLetters

## What's this?
Fully scrollable and animated letters animation system, make in pure JS.

## How to use?

```
<section class="scrolL">
    <div class="scroll-container">
        {your text}
    </div>
</section>
```

or you can self-defined letters with
```
<span class="scroll-item">{char(1)}</span>
```

## Parameters

The following parameters could be used on the ```.sroll-container``` to custom animation.

### Offsets

By default animation starts and ends at the begging and the end of the scroll area, but with offset you can custom it.
```
data-offset="{int:start-offset}-{int:end-offset}"
```

### Scales

Custom starting scale and ending one of each letters.
```
data-scale="{int:end-scale}-{int:start-scale}"
```

### Size

Can define min and max font-size, in px.
```
data-size="{int:min-size}-{int:max-size}"
```

### Spacing

Can add an horizontal padding.
```
data-spacing="{int:spacing}"
```
