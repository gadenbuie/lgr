@Library('jenkins-r-shared-library') _

rBuildPipeline(
  dockerImage: 'library/r-base:3.5.1-devtools-stat',
  mailTo: 'stefan.fleck@statistik.gv.at',
  rPackages: 'knitr,testthat,gepaf,testthis,tibble,rmarkdown, roxygen2',
  githubPackages: '-',
  additionalScript:'-',
  ignoreCheck:'NO'
)
