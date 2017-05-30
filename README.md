# ItemImagePricer
Easily add prices to images to improve sales over social media platforms such as Facebook

## Description

When selling many items on social media platforms such as Facebook, it can be bothersome to repeatedly type the price for each item in each new post, and a lot of users ignore the text whilst they scroll through your images.

To mitigate this, I personally have been using image editing software to manually add the prices to each item image before posting which has greatly increased my conversion ratio and decreased pointless questions and messages. However, manually adding these prices for each item is too lengthy a process, especially when I need to create multiple copies for different currencies.

This script allows you to assign a base price for all of your items (referenced as images in a directory), and automatically add the price tag to each image (as a copy). You cna change the scale factor and run the script again to create another copy in a different currency, for example. It is extremely customisable, allowing you change the display settings for the price tag among other things.

This must be run as an iPython notebook.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installation

You must have Jupyter notebooks installed

You must also enable widgets (for the progress bar):

`jupyter nbextension enable --py --sys-prefix widgetsnbextension`

Then clone the repository (or simply copy the `core.ipynb` file)

`git clone https://github.com/KeirSimmons/ItemImagePricer.git`

Run the notebook

`jupyter notebook core.ipynb`

Option 1: Run with default configuration:

Cell -> Run All 

Option 2: ADVANCED: Modify configuration:

See the `__init__` method of class `ProcessItems`

## Contributing

This was made as a small 1 day code project to speed up my own sales over Facebook, but I have released it here in case others can benefit from my efforts. Feel free to improve upon the codebase or add features, and submit a pull request!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
