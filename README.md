AngularJS 6 Example 3rd, Packtpub book 
9/25/2019, Wed

chp2 last


#steps
ng generate module workout-runner --module app.module.ts
ng generate component workout-runner -is
ng serve --open

#URL
http://localhost:4200/

#mapping
main.ts <- app.module.ts <- app.component.ts
                         <- workout-runner.module.ts <- WorkoutRunnerComponent, ExerciseDescriptionComponent, VideoPlayerComponent, SecondsToTimePipe

#link
https://subscription.packtpub.com/book/web_development/9781788835176/2/ch02lvl1sec27/our-first-component-workoutrunnercomponent

#
 and  are interpolation symbols
[ ] - represents property bindings
( ) - represents event bindings
*ngIf - NgIf

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
