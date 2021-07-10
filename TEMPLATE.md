<div align="center"><img src="https://readme-typing-svg.herokuapp.com?font=&color=000000&lines=Hi!+I'm+Sai+Kishore;I+Code...;I+Draw...;I+Write" /></div>
  
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shadow-prince&theme=default)
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=shadow-prince&theme=default)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=shadow-prince&theme=default)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=shadow-prince&theme=default)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=shadow-prince&theme=default)

<details>
  <summary>Wanna Know More?</summary>
  <br>

 Account age: **{{ ACCOUNT_AGE }}** years

Pushed **{{ COMMITS }}** commits

Opened **{{ ISSUES }}** issues

Submitted **{{ PULL_REQUESTS }}** pull requests

Received **{{ STARS }}** stars

Own **{{ REPOSITORIES }}** repositories

Contributed to **{{ REPOSITORIES_CONTRIBUTED_TO }}** public repositories

**Top 8 most used languages across my repositories:**

{{ LANGUAGE_TEMPLATE_START }}
![{{LANGUAGE_NAME}}](https://img.shields.io/badge/{{LANGUAGE_NAME:uri}}-{{LANGUAGE_PERCENT:uri}}%25-{{LANGUAGE_COLOR:uri}}?style=for-the-badge&logo={{LANGUAGE_NAME:uri}})
{{ LANGUAGE_TEMPLATE_END }}

</details>


#### 👷 Check out what I'm currently working on
{{range recentContributions 10}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}

#### 🌱 My latest projects
{{range recentRepos 10}}
- [{{.Name}}]({{.URL}}) - {{.Description}}
{{- end}}

