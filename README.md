# Mini-Projet de Sécurité AWS

## Introduction

Ce projet a pour objectif de renforcer la sécurité des applications déployées sur AWS. On agira en tant que SysOps administrator pour mettre en œuvre des mesures de sécurité essentielles à l'infrastructure cloud de l'entreprise. Notre travail portera principalement sur la gestion des secrets, la configuration d'une ACL web et la préparation d'une instance EC2 pour l'intégration avec Amazon Inspector.

![image](https://github.com/user-attachments/assets/2da0f00a-9f02-4989-8d7d-621a5f1f68af)




## Objectifs

- Supprimer les secrets d'un modèle AWS CloudFormation pour sécuriser les informations sensibles.
- Configurer un Web Application Firewall (WAF) pour protéger l'application web contre les attaques courantes.
- Assurer que les instances EC2 sont configurées pour fonctionner avec AWS Systems Manager, afin de les préparer pour Amazon Inspector.

## Liste des Services Utilisés

- **AWS WAF**: Protection des applications web contre les attaques courantes.
- **AWS Security Hub**: Centralisation et automatisation de la gestion de la sécurité.
- **AWS IAM**: Gestion des accès aux services AWS.
- **EC2**: Service de calcul pour héberger les instances.
- **Amazon Inspector**: Analyse automatique des vulnérabilités des instances EC2.
- **AWS Secrets Manager**: Gestion sécurisée des secrets et des informations sensibles.
- **AWS Config**: Surveillance de la conformité et de la configuration des ressources AWS.
- **AWS CloudFormation**: Déploiement de l'infrastructure en tant que code.


## Étapes du Projet

1. **Suppression des Secrets**:
   - Identifier et supprimer les secrets stockés dans le modèle CloudFormation.
   - Remplacer les secrets par des références à AWS Secrets Manager.

2. **Configuration d'une ACL Web**:
   - Créer et configurer un Web Application Firewall (WAF) pour l'application web.
   - Définir des règles de sécurité pour bloquer les requêtes malveillantes.

3. **Configuration d'EC2 pour Systems Manager**:
   - Configurer les instances EC2 pour qu'elles soient prêtes à fonctionner avec AWS Systems Manager.
   - Vérifier que les instances sont configurées pour être analysées par Amazon Inspector.

## Conclusion

Ce mini-projet nous permet d'acquérir une expérience pratique dans l'utilisation des services de sécurité AWS pour protéger les applications web et les infrastructures cloud. En suivant les étapes décrites, nous renforcerons la sécurité des applications de l'entreprise en adoptant des meilleures pratiques d'AWS.

