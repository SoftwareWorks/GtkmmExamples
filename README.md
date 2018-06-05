
# Gtkmm Examples

Shows how to use Gtkmm controls by programming code (c++14).

## Hello World

["Hello World"](src/HelloWorld) The classic first application HelloWorld with Gtk::Label.

## Application and messages

[Application](src/Application) Shows how to create a simple Gtkmm application with Gtk::Application.

## Common Controls

[Button](src/Button) Shows how to create a Gtkmm Button and Event Click with Gtl::Button.

[CheckBox](src/CheckBox) Shows how to create a Gtkmm CheckBox with Gtk::CheckButton.

[Label](src/Label) Shows how to create a Gtkmm Label with Gtk::Label.

[ProgressBar](src/ProgressBar) Shows how to create a Gtkmm ProgressBar with Gtk::ProgressBar.

[RadioButton](src/RadioButton) Shows how to create a Gtkmm RadioButton with Gtk::RadioButton.

[TextBox](src/TextBox) Shows how to create a Gtkmm TextBox with Gtk::Entry.

[TrackBar](src/TrackBar) Shows how to create a Gtkmm TrackBar with Gtk::Scale.

## Containers

[Form](src/Form) Shows how to create a simple Gtkmm Form with Gtk::Window.

[GroupBox](src/GroupBox) Shows how to create a simple Gtkmm GroupBox with Gtk::Frame.

[Panel](src/Panel) Shows how to create a simple Gtkmm Panel with Gtk::Frame.

[TabControl](src/TabControl) Shows how to create a simple Gtkmm TabControl with TabPages with NSTabView and Gtk::Notebook.

## Menus and toolbars

[MainMenu](src/MainMenu) Shows how to create a Gtkmm MainMenu with NSMenu and Gtk::MenuBar.

## Components

[Timer](src/Timer) Shows how to create a simple Gtkmm Timer with TimerGtk.

## Dialogs

[ColorDialog](src/ColorDialog) Shows how to create a ColorDialog with Gtk::ColorChooserDialog.

[MessageBox](src/MessageBox) Shows how to create a MessageBox with Gtk::MessageDialog.

## Download

``` shell
git clone https://github.com/gammasoft71/GtkmmExamples GtkmmExamples
```

## Generate and build

To build this project, open "Terminal" and type following lines:

``` cmake
mkdir build
cd build
cmake .. 
cmake --build . --config Debug
```

## Remarks

This project run only on macOS with [Gtkmm 3](https://www.gtkmm.org) and [CMake](https://cmake.org).