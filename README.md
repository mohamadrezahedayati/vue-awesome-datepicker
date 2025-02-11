
<center>
<a align="center" href="https://github.com/MohammadS3dd/vue-awesome-datepicker">
	<img src="https://raw.githubusercontent.com/MohammadS3dd/vue-awesome-datepicker/master/docs/dp-banner.PNG"  />
</a>
</center>


# Vue Awesome Datepicker 


awesome, zero dependency, performant Vue datepicker component


<br><a href="https://mohammads3dd.github.io/vue-awesome-datepicker/"><b>Demo</b></a>

## Installation 🚀
```bash
npm i vue-awesome-datepicker
# or 
yarn add vue-awesome-datepicker
```


## Component Registration and usage

```javascript

import datepicker from "vue-awesome-datepicker";

import "vue-awesome-datepicker/dist/font-default.css"; //if you want default fonts

export default {
  components: {
    datepicker,
  },
  data() {
    return { date: {},dateGreg:{} };
  },
};

<template>
  <datepicker lang="Jalali" type="multiple" colorTheme="pink" v-model="date" />
  <datepicker lang="Greg" type="range" colorTheme="yellow" v-model="dateGreg" />
</template>

```

# Props
## `lang`
string ( Jalali | Greg )
## `type`
string ( range | multiple | single )
## `colorTheme`
string ( Yellow | Pink )
## `date`
object
## `debugSelector`
object
## `preSelectedModel`
object
## `holidayMap`
object
## `disabledMap`
object
## `events`
array
## `forwardLimit`
object
## `backwardLimit`
object
## `selectable`
object

# Contribution
## TODO 

- [X] decouple styles from tailwind CSS
- [ ] refactor to composition api
- [ ] add customizability
- [ ] documentaition
