# scattergrid
extenstion to scatterplot3d package.

## Presentation
This is a modified version of [scatterplot3](dhttp://cran.r-project.org/web/packages/scatterplot3d/index.html).

The function `scatterplot3d()` from the scatterplot3d package only plots the grid for XY-plane. `sactter.grid` , extends this so you can draw the grid for YZ- and XZ- planes as well. 

A using example is :

      z <- seq(-10, 10, 0.01)
      x <- cos(z)
      y <- sin(z)
      sactter.grid(x, y, z, highlight.3d=TRUE,
                    col.axis="blue",
                    grid=c('xy','xz','yz'),  ## add grid to all facets
                col.grid="lightblue")
                

## Install       
    
     library(devtools)
     install_github('agstudy/scattergrid')


                



                
                
             
