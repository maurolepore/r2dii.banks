FROM rocker/binder:3.6.3
LABEL maintainer='Mauro Lepore'
USER root
RUN echo "To learn what you can do with r2dii.analysis, visit https://2degreesinvesting.github.io/r2dii.analysis/" > README.md
RUN chown -R ${NB_USER} ${HOME}
USER ${NB_USER}



RUN wget https://github.com/maurolepore/r2dii.banks/raw/master/DESCRIPTION && R -e "options(repos = list(CRAN = 'http://mran.revolutionanalytics.com/snapshot/2020-06-25/')); devtools::install_deps()"

RUN rm DESCRIPTION.1; exit 0
