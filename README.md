# mastodon-faq-fr

La FAQ n'est pour le moment pas organisée, je jette ici les questions que l'on me pose fréquemment.

# Mastodon lui même
## Qui a créé Mastodon ?

Eugen, [@Gargron@mastodon.social](https://mastodon.social/@Gargron)

## Je ne comprends rien, il y a une introduction ?

Il existe des documents créés par des utilisateurs comme [Welcome to Masotond par Aldarone](https://aldarone.fr/welcome-to-mastodon/)

# Fonctionnement des instances

## Si je suis sur une instance, puis-je discuter avec des personnes sur une autre instance ?

Oui. Les instances discutent entre elles pour que les utilisateurs de chaque instance puissent communiquer.

L'ensemble de ces instances se nomme le Fediverse (Contraction de Federation / Universe).

## Peut-on migrer son compte d'une instance à une autre ?
Réponse courte : NON

Réponse longue, la bonne pratique est de suivre ces étapes :
1. Créer un compte sur la nouvelle instance
2. Renommer son ancien compte pour y inclure le préfixe [MIGRE]
3. Écrire un dernier toot sur l'ancien compte en indiquant la migration et en spécifiant le nouveau compte.

Il est possible d'exporter puis d'importer la liste de ses abonnements, pas les abonnés ainsi que la liste des personnes bloquées.

## Pourquoi ne puis-je pas m'inscrire sur certaines instances ?
L'administrateur de ces instances n'a pas ouvert les inscriptions, ce sont des instances privées ou publiques devenues fermées pour préserver les ressources sur l'instance.

## Ais-je choisi la bonne instance ?
Pour choisir une instance, il convient de se renseigner sur :
1. Ses règles. Celles-ci précisent notamment les contenus autorisés et les comportements attendus de la part des utilisateurs.
2. Ses administrateurs. Un administrateur peut, s'il souhaite s'en donner la peine, obtenir vos messages privés, adresse de courriel, et mot de passe. Si vous tenez à garder ces informations secrètes, assurez-vous de pouvoir faire confiance à l'administrateur de votre instance.
3. Ses caractéristiques techniques. Cette instance se synchronise-t-elle rapidement avec la fédération ? Supporte-t-elle une connexion chiffrée de qualité ? Permet-elle un accès IPv6 ? À quelle fréquence tombe-t-elle en panne ?
Ces informations peuvent être obtenues sur la page /about/more de l'instance, ou sur [instances.mastodon.xyz](https://instances.mastodon.xyz/) pour les caractéristiques techniques.

# Son compte

## Peut-on certifier son compte ?

Non, ce principe n'existe pas contrairement à Twitter.

# Se connecter à Mastodon

## Est-ce qu'il existe un client Mastodon sur smartphone ?
Oui.
Sur iOS, pour iPhone / iPad il y a [Amaroq sur l'AppStore](https://itunes.apple.com/us/app/amaroq-for-mastodon/id1214116200?mt=8) un client gratuit, bien réalisé.

Pour Android il existe [Tusky sur Google PlayStore](https://play.google.com/store/apps/details?id=com.keylesspalace.tusky)

# La modération

## C'est quoi le SILENCE ?

Un administrateur peut poser un tag SILENCE sur un compte, ce compte ne sera lisible que par ses abonnés et ne sera pas visible dans les différentes timelines. Le SILENCE peut être aussi bien posé par l'administrateur de l'instance qui héberge le compte qu'un administrateur d'une autre instance.

# Je suis perdu(e)

## Comment retrouver mes amis de Twitter ?
Le [Mastodon Bridge](https://mastodon-bridge.herokuapp.com) a été conçu à cette fin. Se connecter en utilisant votre compte Twitter et votre compte Mastodon, il listera vos amis de Twitter qui ont aussi utilisé le Mastodon Bridge.
