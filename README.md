# Base-Input
A component to accept input

## Purpose
A pre-built Reusable input component 

## Explaination
[Vue Mastery: Base Input](https://www.vuemastery.com/courses/vue3-forms/base-input)

```
      <BaseInput 
        v-model="event.title" 
        label="Title" 
        type="text" />
```
- event structure (example):
```
  event: {
        category: '',
        title: '',
        description: '',
        location: '',
        pets: 1,
        extras: {
          catering: false,
          music: false
        }
      }
```
- v-model: the object that is being modified ('title' above);
- label: the label seen on the front-end above the input;
- type: the input type

## Prerequisites
None

## Use
1. Clone component into your components folder of your vue project.
2. Call the component in the desired view using the following structure:
   
[```<BaseInput v-model="event.title" label="Title" type="text" />```](https://gist.githubusercontent.com/efwoods/c6dfc080cbd651166367419d9a804bc3/raw/191d87c2426e1a51809148ee11a97d12934f9d91/Base-Input-Component-Impl.vue)