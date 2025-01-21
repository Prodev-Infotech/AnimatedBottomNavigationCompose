# Animated bottom bar

AnimatedBottomBar is bottom navigation bar with customizable animated tabs

![](media/demo.gif)

## How to use

BubbleNavigationBar{
    navigationItems.forEach { navigationItem ->
        BubbleNavigationBarItem(
            selected = currentRoute == navigationItem.route,
            onClick = {
                //Navigate
            },
            icon = navigationItem.icon,
            title = navigationItem.title,
            selectedColor = navigationItem.selectedColor
        )
    }
}
