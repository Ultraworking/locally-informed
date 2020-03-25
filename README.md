# Locally Informed — Regional Data Sources

These are dark times and unfortunately the internet is rife with false information from unverified sources which is spreading paranoia.

[Locally Informed](https://local.quarantinesupport.com/) is a module within [Quarantine Support](https://quarantinesupport.com/), an initiative started by us at [Ultraworking](https://ultraworking.com/) to ensure that the correct information regarding COVID-19 gets filtered down to Netizens.

We have opened Locally Informed to crowdsource data — this means that if you have access to the proper data sources in your city, state or country, and you are a little bit tech-savvy, you can make a contribution to Locally Informed, (_the instructions are below_), and help ensure that the people in your area are as well informed as you are.

Remember, we are only as strong as our weakest link in our fight against this Pandemic.

**Parati Servire — we are here to serve.**

— The Ultraworking Team

## Directory Structure

![Directory Structure](https://i.ibb.co/5F1XZV1/Screenshot-2020-03-25-at-10-33-55-AM.png)

- **\[COUNTRY_ISO_CODE\]**: The [3-Letter ISO Alpha-3 code](https://www.nationsonline.org/oneworld/country_code_list.htm) for the target country. (Example — `nzl` for New Zealand).
- **\[REGION_NAME\]**: For USA, this will be the 2-Letter State code. (Example — `ca` for California). For all other countries, this will be the name of the target city. (Example — `kuala lumpur` for Kuala Lumpur City, Malaysia).

**NOTE: both the \[COUNTRY_ISO_CODE\] and \[REGION_NAME\] should be in lower case.**

## Contribution Guide — USA

To get started, you will first need to fork and clone the repository. If you are not familiar with contributing to public projects on GitHub the instructions can be found [here](https://opensource.com/article/19/7/create-pull-request-github).

You will then want to navigate to the **regions** folder. (`locally-informed/countries/usa/regions`).

### 1. Add resources to an existing data source for a State:

- Find the JSON file for the State by searching for its 2-Letter State Code. (Example — `ca.json` for California).
- Open the JSON file using a text editor and add the resources by following the file structure.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.

### 2. Create a data source and add resources for a State:

**Note: Make sure that a data source does not already exist for the State**

- Copy the `region_template.json` file from `locally-informed/templates`.
- Paste the copied `region_template.json` file into `locally-informed/countries/usa/regions`.
- Rename the file with the 2-Letter State Code. Example — `tx.json` for Texas.
- Open the template and follow the structure to add resources. You can use data sources for other States as reference.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.

## Contribution Guide — Rest of the World

To get started, you will first need to fork and clone the repository. If you are not familiar with contributing to public projects on GitHub the instructions can be found [here](https://opensource.com/article/19/7/create-pull-request-github).

### 1. Add resources to an existing data source for a Country:

- Find the JSON file for the Country by searching for its [3-Letter ISO Alpha-3 code](https://www.nationsonline.org/oneworld/). (Example — `deu.json` for Germany).
- Open the JSON file using a text editor and add the resources by following the file structure.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.

### 2. Create a data source and add resources for a Country:

**Note: Make sure that a data source does not already exist for the Country**

- Copy the `country_template.json` file from `locally-informed/templates`.
- Create a new folder inside `locally-informed/countries`.
- Rename the folder with the [3-Letter ISO Alpha-3 code](https://www.nationsonline.org/oneworld/). (Example — `ita` for Italy).
- Paste the copied `country_template.json` file into the created folder.
- Rename the file with the [3-Letter ISO Alpha-3 code](https://www.nationsonline.org/oneworld/). (Example — `ita.json` for Italy).
- Open the template and follow the structure to add resources. You can use data sources for other Countries as reference.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.

### 3. Add resources to an existing data source for a City:

- Find the JSON file for the City by searching for its City name inside `locally-informed/countries/[COUNTRY_NAME]/regions`. (Example — `warsaw.json` for Warsaw, Poland).
- Open the JSON file using a text editor and add the resources by following the file structure.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.

### 4. Create a data source and add resources for a City:

**Note: Make sure that a data source does not already exist for the City**

- Copy the `region_template.json` file from `locally-informed/templates`.
- Paste the copied `region_template.json` file into `locally-informed/countries/[COUNTRY_NAME]/regions`.
- Rename the file with the respective city name. (Example — `auckland.json` for Auckland, New Zealand).
- Open the template and follow the structure to add resources. You can use data sources for other Cities as reference.
- Save the file and commit and push to a branch in your cloned repository.
- Submit a Pull Request to the **locally-informed** repository.
