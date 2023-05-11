# bspwmRectangleCalculator
A simple script that outputs the appropiate string for bspwm's rectangle taking width and height as arguments, for example:

    bspc rule -a \* -o state=floating rectangle=$(~/.config/sxhkd/size_calculator 60 100) && kitty -e $SHELL -c "neomutt"
    
would create a floating kitty instance of with 60% of the screensize as width and 100% of the screensize as height. It is made so the window is always in the center.
