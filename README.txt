PROJET DE JEAN-WILLIAM PERREAULT

Le projet est d�velopp� en utilisant PHP et Neo4j.

Il est conseill� d'utiliser WAMP pour un d�ploiement rapide et facile.
# ATTENTION il est important d'activer le module APACHE: rewrite_module si ce n'est d�j� fait.

Voici un r�sum� de la structure des dossiers du projet

core: Contient le code source PHP et les sous dossier Controller Model et Vue (MVC)
public: contient les �l�ments accessibles directement par l'utilisateur donc la page index.html, les styles css et le javascript
vendor: contient les librairies externes utilis� (neo4jphp de everyman disponible sur github)

doc: la documentation du projet (Le document word ACME et le script d'initialisation)


Pour facilit� les tests de l'application
dans le dossier doc un fichier nomm� "DatabaseInit.cql" est fournis contenant
Une liste de requ�tes Cypher permettant de cr�er plus rapidement des usagers, un thread et des posts dans ce dernier.


