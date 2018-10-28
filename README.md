Base Class for BBjUIWidgets. Most plugins that represent graphical widgets on the screen will inherit from this base class. It implements stubs for all methods in the BBjControl interface (which sits inside BBj).

Use this base class instead of BBjControl if you implement own plugins for the user interface, as we will make sure that this class reflects potential future changes to the non-public BBjControl interface, which might break your code in the future. 
