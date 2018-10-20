# Tweets of Congress

[Tweets of Congress](http://alexlitel.github.io/congresstweets) is the front-end portion of a project collecting the daily tweets of both houses of Congress, encompassing 1,000+ campaign, office, committee and party accounts. It's designed to be used in concert with the [Congressional Tweet Automator](https://github.com/alexlitel/congresstweets-automator), which creates the content in this repo (among other things). For more information on the process of how everything is compiled, visit the aforementioned repo for the Automator.

The collected tweets are available as JSON datasets, which are generated around midnight EST. You can find them in this repository inside the `data` folder, and they are also linked at the site. To do a little more with the datasets, you may want to check out the [historical-users-filtered.json](https://github.com/alexlitel/congresstweets-automator/blob/master/data/historical-users-filtered.json) dataset -- which contains metadata for all the accounts the project follows for tweet collection -- in the automation repo.

Due to size constraints, archives are limited, and because the automation portion interfaces with low-level Github and Git features, the commit history may be volatile and subject to change. Datasets for previous months from June 2017 onward are available as ZIP archives grouped by month [here](https://archive.org/details/tweetsofcongress). This site is open-source, so feel free to fork or whatever to your heart's content. For any issues or other feedback, file an issue, make a pull request, or [send me an email](mailto:alexlitelATgmailDOTcom).


## Acknowledgments

* Jekyll site is built on [John Otander's Pixyll theme](https://github.com/johnotander/pixyll).
* Dataset was created with the help of the [@unitedstates/congress-legislators](https://github.com/unitedstates/congress-legislators) project.
