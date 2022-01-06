## ggplot

## For next class

* Flip (or tab!) through R4DS and be able to answer (I **WILL** call on you next class) broadly-speaking what each chapter of the book covers
* Pay particular attention to the visualization chapter and be able to answer (I **WILL** call on you next class) what these terms refer to:
  +    mapping
  +    data
  +    geom
  +    stat
  +    position
    
## ggplot2 components

## Quiz Next Class
* Quiz: explain:
  +    mapping
  +    data
  +    geom
  +    stat
  +    position
  
[link](https://rpubs.com/hadley/ggplot2-layers)

##    mapping

A set of aesthetic mappings, specified using the aes() function and combined with the plot defaults as described in aesthetic mappings. If NULL, uses the default mapping set in ggplot().

##    data

A dataset which overrides the default plot dataset. It is usually omitted (set to NULL), in which case the layer will use the default data specified in ggplot(). The requirements for data are explained in more detail in data.

##     Geoms

The name of the geometric object to use to draw each observation. Geoms are discussed in more detail in geom, and the toolbox explores their use in more depth.

##    Geoms 

can have additional arguments. All geoms take aesthetics as parameters. If you supply an aesthetic (e.g. colour) as a parameter, it will not be scaled, allowing you to control the appearance of the plot, as described in setting vs. mapping. You can pass params in ... (in which case stat and geom parameters are automatically teased apart), or in a list passed to geom_params.

##    stat 

The name of the statistical tranformation to use. A statistical transformation performs some useful statistical summary is key to histograms and smoothes. To keep the data as is, use the “identity” stat. Learn more in statistical transformations.

You only need to set one of stat and geom: every geom has a default stat, and every stat a default geom.

Most stats take additional parameters to specify the details of statistical transformation. You can supply params either in ... (in which case stat and geom parameters are automatically teased apart), or in a list called stat_params.

##    position

The method used to adjusting overlapping objects, like jittering, stacking or dodging. More details in position.


