### Automatisointi Jekyll-sivustolle GitHub Actionsilla

Jekyll-sivuston automatisointi GitHub Actionsin avulla on tehokas tapa hallita verkkosivuston rakennus- ja julkaisuprosessia. GitHub Actionsin avulla voidaan luoda työprosesseja, jotka käynnistyvät esimerkiksi koodin päivityksen jälkeen. Tällöin voidaan määrittää automaattinen Jekyll-sivuston rakentaminen ja sen julkaiseminen esimerkiksi GitHub Pagesille.

**Esimerkki GitHub Actions -työnkulusta:**

1. **Rakennus:** Aina kun uusi commit tehdään master-haaraan, GitHub Actions voi käynnistää työnkulun, joka asentaa tarvittavat riippuvuudet, kuten Ruby ja Jekyll, ja rakentaa sivuston.
2. **Testaus:** Voidaan lisätä vaihe, joka tarkistaa, että sivuston rakennus ei ole rikkoutunut ja että kaikki linkit toimivat oikein.
3. **Julkaisu:** Rakennettu sivusto voidaan automaattisesti julkaista GitHub Pagesille tai muuhun hosting-palveluun.

**CI/CD-työkalut web-sovellukselle:**

Web-sovelluksen CI/CD-putkiston rakentamiseksi voidaan käyttää työkaluja kuten Jenkins, Travis CI tai GitHub Actions, jotka automaattisesti testaavat, rakentavat ja julkaisevat sovelluksen. Testauksessa voidaan hyödyntää esimerkiksi Seleniumia, ja rakennusprosessiin voidaan käyttää Dockeria.

[Takaisin](https://niinaemil1a.github.io/pwk2/vko2/)
