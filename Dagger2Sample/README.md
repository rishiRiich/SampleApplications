# Sample app documentation

## Sample app for Dagger2 implementation

Dagger2Sample is a sample project which I created for explaining how the dagger can be included and implemented in your
project. This is project has been done in MVP architecture to keep it simple.

I have been going through lot of tutorials about dagger 2 and I found most of the sample project very complicated.
That's why I decided to create my own project, my intention was to create a sample application with dagger2
in the simplest way possible that even a newbie can understand in no time.

This project is done in MVP architecture

> MainActivity  - View
> MainContract  - Interface between View and Presenter
> MainPresenter - Is the presenter

> DaggerHelper
    > MainDaggerModule  - Module class which hods all the objects to provide dependencies
    > MyDaggerComponent - This is an interface class which helps to communicate between DaggerHelper classes and 
    our dependent classes

>DataHelper
    > Utils - Is a model class where the business logic is implemented


Feel free to contribute or reach out to me for any queries.
