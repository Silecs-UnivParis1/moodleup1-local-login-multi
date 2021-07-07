# Authentification

La page de login multi-sources est installée par le module local_up1_loginmulti.

Elle permet l'authentification via

 1.  un compte Shibboleth local (Paris 1), correspondant à un compte utilisateur LDAP
 2.  un compte Shibboleth externe, avec choix WAYF
 3.  un compte local ("Un compte invité"), correspondant à un compte manuel

Elle est accessible (par exemple) à <https://moodle-test.univ-paris1.fr/local/up1_loginmulti/index.php>.


Cette fonctionalité est implémentée par l'utilisation du paramètre global `alternateloginurl`,
réglable à l'adresse `/admin/settings.php?section=manageauths`.

Voir la documentation Moodle :
[Alternate login URL](https://docs.moodle.org/39/en/Managing_authentication#Alternate_login_URL).
