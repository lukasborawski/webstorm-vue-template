### WebStorm IDE Vue.js new SFC file template

---

Copy code that you can find below and past it in here.

```Preferences ➡️ Editor ➡️ File and Code Templates ➡️ Vue Single File Component```

```vue.js
<template>
#[[$END$]]#
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: '${COMPONENT_NAME}',
  inheritAttrs: false,
})
</script>

<script setup lang="ts"></script>
```

For you personal preference you can add as well styles definition.

```vue.js
<template>
#[[$END$]]#
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: '${COMPONENT_NAME}',
  inheritAttrs: false,
})
</script>

<script setup lang="ts"></script>

<style scoped lang="scss"></style>
```

More about **WebStore IDE** you can find [here](https://www.jetbrains.com/webstorm).
