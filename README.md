# EasyVFL
Swift class that makes it easier to add constraints using VFL

# Getting Started

* Download swift file and add to your xcode project.
* Initialize the class with EasyVFL(parent: UIView)
* * The parent argument will be the UIView you wish to add subviews too
* * You will create multiple instances of EasyVFL

# Current functions and functionality

* addView(name: String, view: UIView)
* * Adds a view to the parent view.
* * Automatically sets translatesAutoresizingMaskIntoConstraints to false
* * name: String that you wish to use as the identifier in your VFL
* * view: UIView that you want to assign to the identifier name

* addViews(_ items: [String: Any])
* * Allows you to directly append the EasyVFL view map

* addVFL(item: String)
* * item: String holding VFL to apply to item

* addVFL(items: [String]
* * Alternate signature of addVFL that allows you to batch-add VFL

# Contributing

* Feel free to make a pull request 🤙
