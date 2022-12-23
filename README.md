# Exploring Sex and Ethnic Representation in the Movie Industry
Rlab - P2 Milestone

## Abstract

 The movie industry has faced criticism in recent years for its lack of representation, which can have negative impacts on [children's development](https://academic.oup.com/jcr/article/32/1/119/1796308?login=true) and [self-esteem](https://journals.sagepub.com/doi/abs/10.1177/0093650211401376?casa_token=qWL-ksfuHq0AAAAA:HXhak7Oc2IDO5k4K9E4jegSGUxQl5SP-lsz5972E6aiIQyR3Ns0IIWdmHFhANhDLR2hvFKM-g6SAEMI).
 
 This study aims to examine the extent to which the film industry accurately represents today's society in terms of sex and ethnicity. To do this, we will analyze data from the CMU Movie Summary Corpus and an additional dataset on population demographics. Our analysis will focus on the representation of different ethnicities and sexes across various movie genres, geographical areas, and box office success. We will also track the evolution of representation over time to determine if the industry is making progress in better reflecting society.
 

## Research questions

In what extent is the film industry displaying an accurate representation of today’s society?
Answering such large question can be done by dividing it in a subset of questions:

A) How accurately is the film industry representing different ethnicities and sexes compared to real-life demographics?

B) In what areas (e.g. genre, geographical region) is there the most discrepancy in representation?

C) How is this representation evolving over time?


## Methods

**Step 1: Pre-processing data:**

We are cleaning and preparing the datasets for analysis by removing unnecessary attributes and eliminating countries not included in the CMU Movie Summary Corpus.

**Step 2: General Analysis:**

We are conducting preliminary analysis on the CMU Movie Summary Corpus to identify global trends in sex and ethnic representation across various movie genres. We are also examining the evolution of representation over time.

<p align="center">
	Sex Representation across movie genres
</p>
<p align="center">
  <img src="data/Sex_representation_across_movie_genres.png" alt="Sex representation" width="400"/>


_We are observing an important difference between men and women role distribution across the most present movie genres. To continue our analysis, we are looking at the evolution of sex representation over time._


<p align="center">
	Ethnic count across time in US
</p>
<p align="center">
  <img src="data/Ethnic_count_US.png" alt="Ethnicities" width="400"/>

_We are examining the general count of different ethnicities in the US in particular. Some ethnicities are more present than others, but we have seen a big limitation during this analysis: some ethnicities are very particular (e.g. Irish Americans, Italian Americans, African Americans) but others are very vague (e.g. Indians). We are working on addressing these limitations in further analysis._

**Step 3: Going deeper:**

Using statistical tools such as linear regressions and confidence intervals, we are delving deeper into trends identified in the previous step, including:
* Sex and Ethnicity representation are different based on movie genre
* The age of actors differs based on their sex
* Ethnicity and sex representation are different based on movie home country

**Step 4: Constructing the Visualization and Presenting the Data**

We are constructing visualizations and a narrative to effectively communicate the results of our analysis. The website can be found at [this address](https://annalasne.wixsite.com/rlab-ada-project)


## Organisation of the repository

The repository includes:
* A ReadMe file providing an overview of the project
* A storyline outlining the basis for the website
* A notebook containing all the statistical analysis and plots used in the project


## Team organisation

<table class="tg" style="undefined;table-layout: fixed; width: 342px">
<colgroup>
<col style="width: 164px">
<col style="width: 178px">
</colgroup>
<thead>
  <tr>
    <th class="tg-0lax"></th>
    <th class="tg-0lax">Tasks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">@anlasne</td>
    <td class="tg-0lax">Determine which visualizations to perform on the dataset<br><br>Dataset exploration<br><br>Develop the final text for the data story and web page</td>
  </tr>
  <tr>
    <td class="tg-0lax">@NicolasRR</td>
    <td class="tg-0lax">Plot generation and data exploration for the different genres and ethnicities<br><br>Data exploration and code optimization<br><br>Contribute to the data story</td>
  </tr>
  <tr>
    <td class="tg-0lax">@tototobo</td>
    <td class="tg-0lax">Determine and perform the statistical analyses<br><br>Analyze correlations to improve the findings on the data<br><br>Develop the final text for the notebooks and story</td>
  </tr>
  <tr>
    <td class="tg-0lax">@Matthieu-Andre</td>
    <td class="tg-0lax">Plot generation for sex representation and movies genres<br><br>Dataset exploration and code optimization<br><br>Contribute to the data story</td>
  </tr>
</tbody>
</table>


