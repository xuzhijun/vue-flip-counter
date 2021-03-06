# vue-flip-counter
---

Flip counter for Vue.js

[Demo](https://toaonly.github.io/vue-flip-counter/)


# Getting Started
```
npm install --save vue-flip-counter
```

# Initialization
```
import Vue from 'vue'
import VueFlipCounter from 'vue-flip-counter'

Vue.use(VueFlipCounter);
```

# How to use
```
<FlipCounter
    v-model="value"
    size="75"
    :interval="1000"
    mode="up"
/>
```

## Parameters
| Parameter | Type | Default |
|---|---|---|
| `size` | `string`, `number` | `75` |
| `interval` | `string`, `number`, `false` | `1000` |
| `mode` | `'up', 'down'` | `'up'` |
| `min` | `number`(`0` ~ `9`) | `0` |
| `max` | `number`(`0` ~ `9`) | `9` |
| `trigger` | `{ value: number, event(): void }` | `null` |
