# Model for simple tracking of cells' generation

* uses `generation` as a custom data variable
* uses `custom_division_function` in `custom_modules/custom.cpp` which increments `generation`
* Note that this model only does the simple task of tracking a cell's generation; it does not do cell progeny which requires tracking the parent of a cell.

![](images/custom_data.png)

![](images/plot_generations.png)
