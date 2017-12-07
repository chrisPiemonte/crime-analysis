# Association Rule Mining from <br /> Spatial Data for Crime Analysis

### Abstract
The aim of this project is to examine data regarding the spatial distribution of crimes committed within a year in the city of Charlotte - NC, in the United States of America. There are data collected from about 60,000 crimes, as well as district census data and information on commercial business activities.

Therefore, we intend to apply algorithms for the discovery of Association Rules between variables, so look for associations between the available information.
The Knowledge Discovery process is applied and filters are applied to rules to select only rules with the type of crime in the consequent, because these were those more relevant as they showed where, at the occurrence of the conditions
present in the antecedent of the rule, the various types of crime are more likely to manifest.
<table>
 <tr>
  <td><strong>Alcoholic Drinking Places</strong> </td>
  <td><strong>Crimes</strong></td>
 </tr>
 <tr>
  <td><img src="https://github.com/chrisPiemonte/crime-analysis/blob/master/resources/alcohol_crime_map.png?raw=true"/></td>
  <td><img src="https://github.com/chrisPiemonte/crime-analysis/blob/master/resources/crime_map.png?raw=true"/></td>
 </tr>
</table>

### Setup
I suggest to setup a virtual environment using [miniconda](http://conda.pydata.org/miniconda.html)

1. Create an environment with python 2.7: <pre>conda create --name crime_env python=2.7</pre>

2. Switch to that environment: <pre>source activate crime_env</pre>

3. Install requirements: <pre>pip install -r ./requirements.txt</pre>

4. Check the examples: <pre>jupyter-notebook</pre>

