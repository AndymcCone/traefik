# Docker microservices with traefik

Kolmen Docker imagen kokonaisuus. Traefik tuottaa kahdelle muulle palvelulle Reverseproxyn, Loadbalancingin sekä itsesertifioiudun HTTPS yhteyden.
Nginx imagella tuotetulla frontend-palvelulla on lisäksi käytössä perustason authentikointi. <br />

Palvelut: <br />

Dockeraiheinen nettisivu:   http://localhost/frontend   (Käyttäjätunnus: test, salasana: test.) <br />
Traefik Dashboard:          http://localhost:8080/dashboard#/ <br />
Traefik Whoami:             https://localhost/<br />
