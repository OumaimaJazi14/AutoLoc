###### \# AutoLoc

###### 

###### Plateforme de gestion de location de véhicules multi-agences.

###### Projet réalisé dans le cadre du module UP ASI (Architecture des Systèmes d'Information) à ESPRIT.

###### 

###### \## Objectifs du projet

###### 

###### \- Gérer le parc de véhicules de plusieurs agences de location

###### \- Gérer les clients, les réservations et les contrats de location

###### \- Exposer une API REST documentée (Swagger / springdoc-openapi)

###### \- Mettre en pratique une architecture Spring Boot en couches (Controller, Service, Repository)

###### 

###### \## Stack technique

###### 

###### \- Java 21 (compatible 17+), Maven

###### \- Spring Boot, Spring Data JPA, Spring MVC

###### \- MySQL (XAMPP, port 3307), H2 pour les tests

###### \- Lombok, Postman, Git/GitHub, IntelliJ IDEA Ultimate

###### 

###### \## Acteurs

###### 

###### | Acteur | Rôle |

###### |---|---|

###### | Client | Consulte les véhicules, réserve et loue un véhicule |

###### | Agent d'agence | Gère les réservations, les retours et l'état des véhicules |

###### | Responsable d'agence | Supervise l'agence, gère les agents et suit l'activité |

###### | Administrateur | Gère les agences, les utilisateurs et la configuration globale |

###### 

###### \## Cas d'utilisation (v0)

###### 

###### \*\*Client\*\*

###### \- Consulter les véhicules disponibles

###### \- Réserver un véhicule

###### \- Annuler une réservation

###### \- Consulter son historique de locations

###### 

###### \*\*Agent d'agence\*\*

###### \- Enregistrer un client

###### \- Valider une réservation et créer un contrat

###### \- Enregistrer le retour d'un véhicule

###### \- Mettre à jour l'état d'un véhicule

###### 

###### \*\*Responsable d'agence\*\*

###### \- Gérer les agents de l'agence

###### \- Consulter les statistiques de l'agence

###### \- Gérer le parc de véhicules de l'agence

###### 

###### \*\*Administrateur\*\*

###### \- Gérer les agences

###### \- Gérer les comptes utilisateurs et les rôles

###### \- Superviser la plateforme

###### 

###### \## Environnement

###### 

###### JDK 21, IntelliJ IDEA Ultimate, MySQL 8 (base `autoloc\_db`, port 3307), Postman (collection `AutoLoc-API`), Git.

