# Angular

### Contents

1. [Angular Framework](https://github.com/RukshanDias/Angular#1-angular-framework) </br>
2. [Components & Modules](https://github.com/RukshanDias/Angular#2-components--modules) </br>

---

## 1. Angular Framework

#### 1.1 What is Angular?

-   A component based framework for building structured, scalable and SPA for client side.

#### 1.2 What are Angular advantages?

-   Component based architecture.
-   Cross platform & open source.
-   Reuseable code (services).

#### 1.3 Angular vs AngularJs?

![Angular vs AngularJs](assets/angular%20vs%20angularJs.png)

#### 1.4 What's NPM?

-   Node Package Management. manage open source packages that can be used in project.

#### 1.5 What's CLI tool?

-   Command line interface that use to initialize & develop Angular apps.
-   Can create components, services, modules, etc.
-   Wll automatically register the created elements also.

---

## 2. Components & Modules

#### 2.1 What're Components?

-   Basic UI building block of an Angular app.
-   Normally there are 4 files in a Angular component.
    -   CSS - Styling file. Can also be scss, sass
    -   HTML - template file.
    -   TS - file that link all the component files.
    -   spec.ts - unit test file.

#### 2.2 What's Selector & Template?

![](assets/@Component.png)

-   selector is used to identify each component uniquely.
-   Template is the HTML view of the component.

#### 2.3 What's a Module?

-   A place where you can group the components, directives, pipes and services which are related to the component.
    ![](assets/@NgModule.png)
-   **declarations** - components that the module can have.
-   **imports** - use services of other modules.
-   **providers** - _related to dependency injection_
-   **bootstrap** - which component will be bootstrapped out of declared components.

#### 2.4 How Angular app gets loaded?

1. **index.html** - Single page of the app. index.html will invoke main.js which is the JS version of Main.ts.
2. **Main.ts** - Entry point of webapp. It bootstraps the AppModule ro run on the browser.
3. **app.module.ts** - AppModule wii bootstrap AppComponent.
4. **App-component** - Final View. All other components get here.

#### 2.5 What's Bootstrapped Module & Component?

-   When Angular app starts, the first module/component to launch is the bootstrapped one. (in short - 1st to launch).

---
