---
title: "About HCNC"
---

*Human Capital in the Nordic Countries* is an international collaboration between computer scientists, economists, historians and other social scientists. The project is developing and applying novel machine learning techniques to harvest data from an extensive range of source materials dating back to the 1600's relating to educational attainment across northern Europe. We have commenced work on records from Denmark and Norway, with Sweden and Finland to come later.

The HCNC programme is structured as a natural sequence of work packages. The first step lays the foundations for analysis: the construction of an individual-level database of human capital, drawing on official records (from high schools, technical institutes and universities) and comprehensive biographies of graduates. The new database will support a richer measure of human capital, which takes account of education quality and the heterogeneity of skills acquired by individuals. A key task in association with the creation of the database is critical examination of the source materials — rigorously testing their credibility and accuracy.

Among other things, our analysis considers:
- on the supply side, who received an education? How did the profile of graduates change as access to education expanded? Put another way, what was the effect of education on employment outcomes and social mobility?
- on the demand side, what motivated employers’ choice of formally trained graduates rather than ‘raw’ labour that could be trained on the job? What did the increase in skilled labour mean for productivity at the firm- or industry-level?

## Team

The following people are members of our research team:
{% for team_member in site.team | sort: "surname" %}
- **{{ team_member.firstname }} {{ team_member.surname }}**, {{ team_member.position }}, {{ team_member.institution }}
{% endfor %}
