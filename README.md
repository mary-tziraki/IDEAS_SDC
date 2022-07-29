# Introduction to Working with MRI Data in Python

[![Create a Slack Account with us][create_slack_svg]][slack_heroku_invite]
[![Slack Status][slack_channel_status]][slack_channel_url]
[![Binder][binder_svg]][binder_url]

An introduction to working with magnetic resonance imaging (MRI) data in Python. 

The material from today's workshop has been inspired by the [Intro to MRI](https://carpentries-incubator.github.io/SDC-BIDS-IntroMRI/index.html) and [Structural MRI](https://carpentries-incubator.github.io/SDC-BIDS-sMRI/) MRI software carpentries. 

## About the Lesson

Today's session teaches:

- image manipulation and analysis using python
- getting MRI scans from a scanner into a workable format
- how to align or 'register' MR images
- how process MR images ready for analysis and check quality
- analysing data from MR images

## Episodes

| # |  Episode | Time | Question(s) |
|--:|:---------|:----:|:------------|
| 1 | [2D Images](code/01-2d-images.ipynb) | 30 | What is an image? |
| 2 | [3D Images](code/02-3d-images.ipynb) | 30 | What is a 3D image? |
| 3 | [Medical Images: Scanner to Computer](code/03-medical-images-scanner-to-computer.ipynb) | 30 | How to convert MRI scans to images? |
| 4 | [MRI Modalities](code/04-mri-modalities.ipynb) | 30 | What types of MRI are there? |
| 5 | [Image Registration 101](code/05-image-registration.ipynb) | 30 | How do we align images? |
|   | LUNCH BREAK | 60 |  |
| 6 | [Image Cleanup](code/06-sMRI-image-cleanup.ipynb) | 40 | How to prepare MR images for analysis? |
| 7 | [Spatial Normalisation](code/06-sMRI-image-cleanup.ipynb) | 40 | How do we align many images for analysis? |
| 8 | [Segmentation and Parcellation](code/08-sMRI-segmentation-parcellation.ipynb) | 20 | How do we extract biological measures for analysis? |
| 9 | [Quality Control]| 20 | What can go wrong when processing MRI data? |
| 9 | [Statistical Analysis and Reproducibility] | 30 | How do we extract biological measures for analysis? |

## Contributing

We welcome all contributions to improve the lesson! Maintainers will do their best to help you if you have an
questions, concerns, or experience any difficulties along the way.

We'd like to ask you to familiarize yourself with our [Contribution Guide](CONTRIBUTING.md) and have a look at
the [more detailed guidelines][lesson-example] on proper formatting, ways to render the lesson locally, and even
how to write new episodes.

Please see the current list of [issues][link_issues] for ideas for contributing to this
repository. For making your contribution, we use the GitHub flow, which is
nicely explained in the chapter [Contributing to a Project](http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project) in Pro Git
by Scott Chacon.
Look for the tag ![good_first_issue](https://img.shields.io/badge/-good%20first%20issue-gold.svg). This indicates that the maintainers will welcome a pull request fixing this issue.

## Maintainer(s)

Current maintainers of this lesson are

- [David Cash]
- [Mary Tziraki]
- [Tom Veale]

## Authors

A list of contributors to the lesson can be found in [AUTHORS](AUTHORS)

## License

Instructional material from this lesson is made available under the Creative
Commons Attribution (CC BY 4.0) license. Except where otherwise noted, example
programs and software included as part of this lesson are made available under
the MIT license. For more information, see [LICENSE](LICENSE.md).

## Citation

To cite this lesson, please consult with [CITATION](CITATION)

[create_slack_svg]: https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg
[slack_heroku_invite]: https://swc-slack-invite.herokuapp.com
[slack_channel_status]: https://img.shields.io/badge/Slack_Channel-neuroimaging-E01563.svg
[slack_channel_url]: https://swcarpentry.slack.com/messages/CCJBHKCHZ
[binder_svg]: https://mybinder.org/badge_logo.svg
[binder_url]: https://mybinder.org/v2/gh/carpentries-incubator/SDC-BIDS-IntroMRI/gh-pages?filepath=code%2F
[episode01]: https://github.com/conp-pcno-training/SDC-BIDS-IntroMRI/blob/gh-pages/files/neuroimaging_analysis_at_scale.pptx
[episode02]: https://github.com/conp-pcno-training/SDC-BIDS-IntroMRI/blob/gh-pages/code/02-anatomy-of-nifti/02-anatomy-of-nifti.ipynb
[episode03]: https://github.com/conp-pcno-training/SDC-BIDS-IntroMRI/blob/gh-pages/files/neuroimaging_analysis_at_scale.pptx
[episode04]: https://github.com/conp-pcno-training/SDC-BIDS-IntroMRI/blob/gh-pages/code/04-open-mri-datasets/04-open-mri-datasets.ipynb
[lesson-example]: https://carpentries.github.io/lesson-example
[link_issues]: https://github.com/conp-pcno-training/SDC-BIDS-IntroMRI/issues
[michael_joseph]: https://github.com/josephmje
[jerrold_jeyachandra]: https://github.com/jerdra
