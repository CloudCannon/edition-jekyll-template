---
title: 1.3 Configurer l'apparence de la page d'accueil
category: 1. Configurer Decidim
order: 4
---
Les principaux éléments de configuration de la page d'accueil de la plateforme se trouvent dans l'onglet **Apparence**.

*Consultez [demo.decidim.opensourcepolitics.eu](https://demo.decidim.opensourcepolitics.eu) pour suivre l'exemple.*

![config-apparence]({{site.baseurl}}/uploads/1-3-1-config-apparence.png)

1. **Montrer les statistiques** : Affiche en bas de la page d'accueil des statistiques globales de participation sur la plateforme (nombre d'inscrits, de concertations, de propositions, de réponses aux enquêtes, etc.). Il est nécessaire d'activer un système externe comme Matomo pour obtenir des statistiques que fréquentation (nombre de visiteurs et de pages vues, etc.).
2. **Description** : C'est le texte d'introduction qui s'affiche en dessous de la bannière principale. Ces quelques lignes permettent d'expliquer les objectifs de la plateforme. Il est possible d'inclure un lien vers une autre page de la plateforme. Un bouton "s'inscrire" est positionné sous ce texte pour les visiteurs qui ne sont pas connectés.
3. **Texte de bienvenue** : Principal message d'accueil, qui peut être décliné pour mettre en avant la concertation/actualité du moment. Par défaut, le texte est "Bienvenue sur nom-de-la-plateforme". Nous recommandons de ne pas dépasser 50 caractères pour ce titre. Il est possible de n'écrire aucun texte en inscrivant un espace HTML : ![blank-space-html]({{site.baseurl}}/uploads/1-3-2-blank-space-html.png)
4. **Image de la page d'accueil** : Bannière principale, au format recommandé de 2880 x 1800 px. *Attention : si vous cherchez à écrire un message sur l'image, l'affichage responsive peut décaler le texte dans une zone non visible sur smartphone !*
5. **Chemin & Texte du bouton d'action** : Par défaut, le texte "Participez" s'affiche et le bouton renvoie vers la liste de toutes les concertations. Avec ces deux champs, vous pouvez modifier le texte et le lien de redirection, par exemple pour diriger les utilisateurs vers une notice "Comment ça marche ?" ou un vote décisif.
6. **Bannière de contenu mis en valeur** : Cette bannière secondaire se place entre la description et la liste des concertations en cours. Elle est très pratique pour mettre en avant une étape ou un contenu important de la plateforme.
7. **Bannière d'actualités** : Si vous l'activez, elle apparaîtra sur toutes les pages du site, au-dessus de la barre de navigation et généralement dnas une couleur qui crée du contraste. Elle est donc très efficace pour attirer les utilisateurs vers un contenu.
8. **Logo** : C'est le logo principal de la plateforme, qui n'est souvent pas celui de l'institution. La définition recommandée va jusqu'à 456 x 148 px, mais par défaut la barre de navigation fait 148 px de haut et l'espace réservé au logo n'est que de 44 px ; nous vous conseillons donc d'utiliser un logo horizontal pour gagner en lisibilité. Vous pouvez nous [demander une modification du CSS]({{site.baseurl}}/configurer-decidim/modification-css-plateforme/) pour agrandir cette barre.
9. **Icône** : Favicon au format carré (80 x 74 px) qui sera visible dans l'onglet de votre navigateur.
10. **Logo officiel - barre de navigation** : Logo facultatif qui renvoie directement vers le site de l'institution. Il est collé à la marge droite de l'écran, dans une hauteur de 38 px, mais nous recommandons une définition de 271 x 88 px.
11. **Logo officiel - pied de page** : Logo facultatif qui renvoie directement vers le site de l'institution. Sa taille indiquée est de 64 x 64 px. Il arrive que son positionnement soit capricieux - n'hésitez pas à nous solliciter en cas de problème.
12. **URL officielle de l'organisation** : C'est l'adresse du site de l'institution vers lequel redirige les logos officiels de barre de navigation et de pied de page. *Attention : il est indispensable d'écrire "http://nom-de-domaine" (ou https:// bien entendu) sinon Decidim pense qu'il s'agit d'un lien interne à la plateforme.*
13. **Eléments à ajouter entre les balises HTML** (réglage avancé) : Ce champ permet de surcharger le code CSS de la plateforme pour modifier l'affichage (masquer une section, changer la couleur d'un bouton particulier, etc.). Il est également possible d'intégrer ici le script d'un tracker de fréquentation Matomo ou Google Analytics.
14. **Mettre à jour** : N'oubliez pas de mettre à jour votre page pour ne pas perdre vos modifications !

![apparence-home]({{site.baseurl}}/uploads/1-3-3-apparence-home.png)

--

*Suite : [Demander une modification du CSS]({{site.baseurl}}/1-configurer-decidim/4-modification-css-plateforme/)*
