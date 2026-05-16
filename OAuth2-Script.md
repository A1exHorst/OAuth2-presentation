# OAuth 2.0
Das OAuth 2.0-Autorisierungs-Framework ermöglicht es einer Drittanwendung, **begrenzten Zugriff** auf einen HTTP-Service (z. B. ein REST / Web-Server) zu erlangen. 

Der Ressourceneigentümer kann auf zwei wegen der Drittanwendung den Zugriff erlauben, entweder:
- **Über eine direkte Interaktion mit dem Service direkt**
- oder **indem er der Drittanwendung ermöglicht, in ihrem eigenen Namen den Zugriff zu erlangen**

## Analogie zu OAuth2
<img width="480" height="1070" alt="image" src="https://github.com/user-attachments/assets/3ddd6538-6589-4fff-bb75-e303929b4592" />

Auf Android Geräten kann der Nutzer **(Ressourcenbesitzer)** allen Apps **(Drittanbieter)** den Zugriff auf die vom Gerät angebotenen Sensoren **(der Ressourcenserver)** begrenzen / freigeben. 

_Dieses Beispiel ist nur eine Analogie. Android Permissions ist ein Sicherheitsmodell das rein vom Betriebssystem angeboten wird. OAuth2 wird nur in Webanwendungen verwendet._

## Reale Beispiele in denen OAuth2 (offensichtlich) angewendet wird

In diesen beispielen wird der **Authorization Code**-Grant verwendet.

<img width="670" height="606" alt="image" src="https://github.com/user-attachments/assets/344aae3e-678b-4c7a-a8e4-e48aed19e655" />

_GitHubs Login Seite_

<img width="562" height="625" alt="image" src="https://github.com/user-attachments/assets/68985862-aa53-4f6f-9460-473d20715cf2" />

_Spotifys Login Seite_

## Quelle
[RFC 6749: The OAuth 2.0 Authorization Framework](https://datatracker.ietf.org/doc/html/rfc6749#section-1)

[Spring Security OAuth2](https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html)
