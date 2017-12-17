# bayesian-filter-resource-list
a bayesian-filter resource list, starting from good intuition and projects with open source codes.

## Kalman Filter
### Tutorial 
* [Special Topics - The Kalman Filter](https://www.youtube.com/watch?v=CaCcOwJPytQ)
* [bobondemon](https://bobondemon.github.io/2017/05/10/Bayes-Filter-for-Localization/)
* [rlabbe](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python)

### Projects 

## Particle Filter 
### Tutorial 
* [Particle Filters Explained
](https://www.youtube.com/watch?v=sz7cJuMgKFg)
* 
### Projects 

* [A particle filter for tracking multiple humans in high-density crowds](https://github.com/NewProggie/Particle-Filter)

  error 1:
  act: "cmake .."

  error message: gsl-config not found.

  solution:
  sudo apt-get install libgsl0-dev
  pkg-config --libs gsl 


  error 2:
  act:"make"
  error message: ‘cvCvtPixToPlane’ was not declared in this scope

  solution:
  change `cvCvtPixToPlane` to `cvSplit`.

* [Particle Filter Object Tracking - Person Crossing](https://www.youtube.com/watch?v=B4ianyQTnCE)

## Contributing

Your contributions are always welcome!
