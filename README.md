# Bookdown Data Trust Agreement

Gitbook version of a BrightHive Data Trust Agreement

## Clauses for the Data Trust Agreement

The standard Data Trust Agreement is composed by putting the following Rmarkdown files in sequence:

- index.Rmd
- recitals.Rmd
- definitions.Rmd
- member_responsibilities.Rmd
- trustee_responsibilites.Rmd
- trustee_affiliate_responsibilities.Rmd
- governance_board.Rmd
- research.Rmd
- publication.Rmd
- proprietary_rights.Rmd
- liability.Rmd
- confidentiality.Rmd
- ethical_use.Rmd
- term.Rmd
- miscellaneous.Rmd
- survival.Rmd
- signatures.Rmd
- exhibit_a_ethical_principles.Rmd
- exhibit_b_governance_board.Rmd
- exhibit_c_goals.Rmd
- exhibit_d_member_resources.Rmd
- exhibit_e_trust_resources.Rmd
- exhibit_f_users_uses.Rmd
- exhibit_g_dags.Rmd
- exhibit_h_tech.Rmd
- exhibit_i_conditions.Rmd
- exhibit_j_change_log.Rmd

------

The report is and can be further parameterized. The folowing parameters are currently defined.

index.Rmd:
- trust_name: (str): title of the trust (e.g. "State of Colorado Workforce Data Trust")
- eff_date: (date, YYYY-MM-DD): date that the trust agreement is formally signed by the MVC.
- members: (semicolon separated list of str): comprised of strings, separated by semicolons, of the legal names of the organizations that are members of the trust.
- trustee: (str): the official legal name of the organization acting as trustee