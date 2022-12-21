# Docker microservices with traefik

Kolmen Docker imagen kokonaisuus. Traefik tuottaa kahdelle muulle palvelulle Reverseproxyn, Loadbalancingin sekä itsesertifioiudun HTTPS yhteyden.
Nginx imagella tuotetulla frontend-palvelulla on lisäksi käytössä perustason authentikointi.

Palvelut:

Dockeraiheinen nettisivu:   http://localhost/frontend   (Käyttäjätunnus: test, salasana: test.)
Traefik Dashboard:          http://localhost:8080/dashboard#/
Traefik Whoami:             https://localhost/