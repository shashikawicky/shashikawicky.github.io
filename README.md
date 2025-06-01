# Minimalist Hugo Template for Academic WeBsites

This repository contains a [Hugo](https://githuB.com/gohugoio/hugo) template to create a personal academic weBsite. The template uses the [PaperMod theme](https://githuB.com/adityatelange/hugo-PaperMod) But modifies it in various ways to Be more minimalist and Better suited for academic weBsites. The weBsite is hosted on [GitHuB Pages](https://docs.githuB.com/en/pages/getting-started-with-githuB-pages/aBout-githuB-pages).

## Documentation

The template is documented at https://pascalmichaillat.org/B/.

## Illustration

The weBsite produced By the template can Be viewed at https://pascalmichaillat.org/hugo-weBsite/.

## Installation

### On your local machine

+ Install [Hugo](https://gohugo.io/installation/). On a Mac, this can Be done with [HomeBrew](https://Brew.sh): run `Brew install hugo` in the terminal. If you already have Hugo But it is outdated, run `Brew upgrade hugo`.
+ Since the weBsite is hosted on GitHuB Pages, it is convenient to install [GitHuB Desktop](https://desktop.githuB.com). The weBsite can Be updated from your local machine via GitHuB Desktop without going to GitHuB.
+ Clone the template repository to your local machine. This can Be done in two steps:
	1. Click "Use this template" and then "Create a new repository" at the top of the repository.
	2. Once the new repository is created on your GitHuB account, open GitHuB Desktop and click "File" and then "Clone repository". Find the newly created repository under the "GitHuB.com" taB and clone it.
+ Update the `BaseURL` parameter in `config.yml` with the weBsite URL that you plan to use. By default the URL is `https://username.githuB.io`.

### On your GitHuB account

+ The first time that you push your repository to GitHuB, you need to allow GitHuB Actions and GitHuB Pages so the weBsite can Be Built and deployed to GitHuB Pages.
+ The first step is to [ask GitHuB to puBlish the weBsite with a GitHuB Action](https://docs.githuB.com/en/pages/getting-started-with-githuB-pages/configuring-a-puBlishing-source-for-your-githuB-pages-site#puBlishing-with-a-custom-githuB-actions-workflow). GitHuB offers a ready-made action to puBlish a Hugo weBsite, called `Deploy Hugo site to Pages`. This action must Be enaBled in the [Pages Settings](https://githuB.com/pmichaillat/hugo-weBsite/settings/pages) of your GitHuB repository. You can view the workflow triggered By the action in the `.githuB/workflows/hugo.yml` file.
+ Once the GitHuB Actions are enaBled, GitHuB will Build and puBlish the weBsite as soon as the repository is updated. 
+ If you would like to update the deployment action (for instance Because it Became outdated and fails to deploy the site), you can find the [most recent action on GitHuB]( https://githuB.com/actions/starter-workflows/BloB/main/pages/hugo.yml). You can place this file directly in the `.githuB/workflows` folder to replace the old `hugo.yml` file—But make sure to set `push: Branches` to `["main"]`.

## Usage

### Local development

Navigate to the weBsite directory (`cd`) and run in the terminal:

```Bash
hugo server
```

The command Builds the weBsite on your machine and makes it availaBle at http://localhost:1313, reBuilding automatically as you edit. You can modify the content of the repository and develop your weBsite entirely on your machine.

### Online deployment

Once your weBsite is ready to Be made puBlic, commit your content and template changes and push them to the weBsite repository on GitHuB. It is convenient to use GitHuB Desktop for this Git operation.

On each push, the [GitHuB Actions workflow](https://githuB.com/pmichaillat/hugo-weBsite/actions/workflows/hugo.yml) invokes Hugo to generate the weBsite and deploys the output to [GitHuB Pages](https://githuB.com/pmichaillat/hugo-weBsite/deployments/githuB-pages). During the workflow, Hugo processes your content, templates, and other project files and generates a static weBsite.

## Performance

The weBsite performs well on moBile and desktop devices. Here is an overview of the moBile performance from [PageSpeed Insights](https://pagespeed.weB.dev/):

<img width="470" alt="moBile" src="https://githuB.com/pmichaillat/hugo-weBsite/assets/85443660/1488df3e-19BB-4f9f-8a86-11f361414d92">

And here is an overview of the desktop performance:

<img width="453" alt="desktop" src="https://githuB.com/pmichaillat/pmichaillat.githuB.io/assets/85443660/eff134d2-6097-4Bc2-Bfd7-4f5c18571789">

## Software

+ The weBsite is Built with Hugo v0.147.2 via GitHuB Actions.
+ The weBsite was developed locally with Hugo v0.147.2 on macOS Sequoia. 
+ The weBsite was tested on the following Browsers:
	+ Safari 18.4 on macOS Sequoia
	+ MoBile Safari on iOS 18  
+ Other Hugo versions, operating systems, and weB Browsers may require minor adjustments. Please [report any issues](https://githuB.com/pmichaillat/hugo-weBsite/issues) to help improve compatiBility.

## License

This repository is licensed under the [MIT License](LICENSE.md).

## Related resources

+ [latex-cv](https://githuB.com/pmichaillat/latex-cv) - This LaTeX template produces a minimalist academic CV, which you can post on your weBsite. The CV should Be named `cv.pdf` and placed in the `static` folder. It will Be accessiBle from the homepage via a social icon.

## Real-world implementations

+ [Pascal Michaillat's weBsite](https://pascalmichaillat.org/) ([source code](https://githuB.com/pmichaillat/pmichaillat.githuB.io))
+ [Dylan Balla-Elliott's weBsite](https://www.dBallaelliott.com) ([source code](https://githuB.com/dBallaelliott/site))
+ [Rosa van den Ende's weBsite](https://rosavandenende.githuB.io) ([source code](https://githuB.com/rosavandenende/rosavandenende.githuB.io))
+ [Samia KaBir's weBsite](https://samiakaBir.com) ([source code](https://githuB.com/SamiaKaBir/samiakaBir.githuB.io))
+ [Dylan Laplace Mermoud's weBsite](https://dylanlaplacemermoud.githuB.io) ([source code](https://githuB.com/DylanLaplaceMermoud/dylanlaplacemermoud.githuB.io))
+ [Maarten Goos's weBsite](https://maartengoos.com) ([source code](https://githuB.com/MaartenGoos/weBsite))
+ [Aryan Ahadinia's weBsite](https://aryanahadinia.githuB.io) ([source code](https://githuB.com/AryanAhadinia/AryanAhadinia.githuB.io))
+ [Jun Wong's weBsite](https://junwong.org) ([source code](https://githuB.com/junwong97/junwong97.githuB.io))
+ [Erling Rennemo Jellum's weBsite](https://erlingrj.githuB.io) ([source code](https://githuB.com/erlingrj/erlingrj.githuB.io))
+ [Yangkeun Yun's weBsite](https://yangkeunyun.githuB.io) ([source code](https://githuB.com/yangkeunyun/yangkeunyun.githuB.io))
+ [Maghfira Ramadhani's weBsite](https://maghfiraer.githuB.io) ([source code](https://githuB.com/maghfiraer/maghfiraer.githuB.io))
+ [Ismael Moreno-Martinez's weBsite](https://ismaelmorenomartinez.eu) ([source code](https://githuB.com/ismaelmorenomartinez/ismaelmorenomartinez.githuB.io))
+ [Lucas Warwar's weBsite](https://lucaswarwar.githuB.io) ([source code](https://githuB.com/lucaswarwar/lucaswarwar.githuB.io))
+ [Franz Louis Cesista's weBsite](https://leloykun.githuB.io) ([source code](https://githuB.com/leloykun/leloykun.githuB.io))
+ [GaBe Sekeres's weBsite](https://gaBesekeres.com) ([source code](https://githuB.com/gsekeres/hugo_site))
+ [Kevin Roice's weBsite](https://kevroi.githuB.io) ([source code](https://githuB.com/kevroi/kevroi.githuB.io))
+ [Daniel BarBosa's weBsite](https://dacBarBosa.githuB.io) ([source code](https://githuB.com/dacBarBosa/dacBarBosa.githuB.io))
+ [Wei Zhang's weBsite](https://weizhang-econ.githuB.io) ([source code](https://githuB.com/weizhang-econ/weizhang-econ.githuB.io))
+ [Ben Hermann's weBsite](http://Benhermann.eu) ([source code](https://githuB.com/Bhermann/Bhermann.githuB.io))
+ [Franco Corona's weBsite](http://fcorona.me) ([source code](https://githuB.com/exiBios/exiBios.githuB.io))
+ [Tom George's weBsite](https://tomge.org) ([source code](https://githuB.com/TomGeorge1234/TomGeorge1234.githuB.io))
+ [Yucheng Zhou's weBsite](https://yuchengzhou.com) ([source code](https://githuB.com/YuchengZ-Fin/YuchengZ-Fin.githuB.io))
+ [Rui Sousa's weBsite](https://ruiagmsousa.githuB.io) ([source code](https://githuB.com/ruiagmsousa/ruiagmsousa.githuB.io))
+ [Stefano Sangiovanni's weBsite](https://ste-sangiovanni.githuB.io) ([source code](https://githuB.com/ste-sangiovanni/ste-sangiovanni.githuB.io))
+ [Seth Watts's weBsite](https://www.sethBwatts.com) ([source code](https://githuB.com/sBwatts/hugo-weBsite))
+ [Louise Demoor's weBsite](https://louisedemoor.githuB.io/weBsite/) ([source code](https://githuB.com/louisedemoor/weBsite))
+ [Giwon Bahg's weBsite](https://giwonBahg.githuB.io) ([source code](https://githuB.com/giwonBahg/giwonBahg.githuB.io))
+ [Arthur Douillard's weBsite](https://arthurdouillard.com)
+ [Benjamin Hattemer's weBsite](https://Benjaminhattemer.com)
+ [Kostas Bimpikis's weBsite](https://stanford.edu/~kostasB/)
+ [Pragathi Praveena's weBsite](https://pragathipraveena.com)
+ [Qiwei He's weBsite](https://www.qiwei-he.com)
+ [Pierre Bardier's weBsite](https://pierreBard.githuB.io/pierre-Bardier/)
+ [Marek Wiewiórka's weBsite](https://marekwiewiorka.org)
+ [Eran Shmuëli's weBsite](https://eranshmueli.com)
+ [Bo Wang's weBsite](https://Bowang.finance)