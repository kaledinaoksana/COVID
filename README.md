# Covid19-Analysis

The project involved analyzing COVID-19 epidemic data to identify trends, patterns, and factors impacting the spread and severity of the virus, providing valuable insights for public health interventions and mitigation strategies.

[Link to full description](http://kaledinaoksana.ru/website/pages/covid.php)

1. Open Docker on MAC (email@gmail.com)
2. Run SQL in Docker
3. Connect SSMS (IPv4 MAC, SA, password) Windows
4. Connect Azure (localhost, SA, password) MAC
5. <https://ourworldindata.org/covid-deaths> - download csv
6. Open dataset in excel, divide table to two
7. Change points to commas
8. Import Wizard Azure

## Connect GitLab from SSH

1. Create ssh

`ssh-keygen -t ed25519 -C "smth"`

`cat id_ed25519.pub`

2. Copy ssh to GitLab

`ssh -T git@gitlab.com`

3. Go to the ptoject:

 *source_gitlab - имя удаленного источника*

`git remote add source_gitlab https://gitlab.com/username/projectname`

`git push source main` 


## Connect Gitlub

1. Github Authorization in Azure Data Studio
2. Go to the ptoject:

*source_github - имя удаленного источника*

`git remote add source_github https://gitlab.com/username/projectname` 

`git push source_github`
