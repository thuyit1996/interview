
1. What do you understand by directives?
 
- Directives add behavior to an existing DOM element or an existing component instance. The basic difference between a component and a directive is that a component has a template, whereas an attribute or structural directive does not have a template and only one component can be instantiated per an element in a template.

- We can differentiate between three types of directives:

  + Components: These directives have a template.
  + Structural directives: These directives change the DOM layout by adding and removing DOM elements.
  +Attribute directives: These directives change the appearance or behavior of an element, component, or another directive.
  
2. JIT vs AOT

 - Angular provides two ways to compile your app. The compilation step is needed as Angular templates and components cannot be understood by the browser therefore the HTML and TypeScript code is converted into efficient JavaScript code.
 - When you run the ng serve or ng build CLI commands, the type of compilation (JIT or AOT) depends on the value of the aot property in your build configuration specified in angular.json. By default, aot is set to true for new CLI apps.
 - Just-in-Time (JIT): JIT compiles your app in the browser at runtime. This was the default until Angular 8.
 - Ahead-of-Time (AOT): AOT compiles your app at build time. This is the default since Angular 9.
 
3. What do you understand by lazy loading?

- By default, NgModules are eagerly loaded, which means that as soon as the app loads, so do all the NgModules, whether or not they are immediately necessary. For large apps with lots of routes, consider lazy loading—a design pattern that loads NgModules as needed. Lazy loading helps keep initial bundle sizes smaller, which in turn helps decrease load times.

4. Can you explain Angular Components Lifecycle Hooks?

ngOnChanges: Is called, when an input/output binding value changes.
ngOnInit: Is called after the first ngOnChanges.
ngDoCheck: Is called, if we as developer triggered a custom change detection.
ngAfterContentInit: Is called after the content of a component is initialized.
ngAfterContentChecked: Is called after every check of the component's content.
ngAfterViewInit: Is called after a component's views are initialized.
ngAfterViewChecked: Is called after every check of a component's views.
ngOnDestroy: Is called just before the directive is destroyed.

5. Change detection, explain how it work?. Zone.js ?
6. What is ViewEncapsulation?
7. Pipe, Pure pipe, impure pipe
8. What is the difference between pure and impure pipe?

- A pure pipe is only called when Angular detects a change in the value or the parameters passed to a pipe. For example, any changes to a primitive input value (String, Number, Boolean, Symbol) or a changed object reference (Date, Array, Function, Object). An impure pipe is called for every change detection cycle no matter whether the value or parameters changes. i.e, An impure pipe is called often, as often as every keystroke or mouse-move.

9. What are dynamic components?
 
Dynamic components are the components in which the component's location in the application is not defined at build time i.e. they are not used in any angular template. Instead, the component is instantiated and placed in the application at runtime.

10. Ngrx
11. Rxjs
