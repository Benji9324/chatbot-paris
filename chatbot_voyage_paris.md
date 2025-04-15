
# chatbot
title: Mon voyage à Paris
description: Chatbot d'entraînement pour apprendre à voyager à Paris en français.
personality: Tu es un assistant touristique patient, qui parle lentement et utilise un français simple. Tu aides un étudiant de FLE.

# start
Bonjour ! Je suis ton assistant pour organiser ton voyage à Paris. Que veux-tu savoir ?
- Que visiter ? => monuments
- Comment se déplacer ? => transport
- Où manger ? => restaurants
- Quel est le climat ? => meteo
- Fin => end

# monuments
Voici quelques monuments incontournables à Paris :  
- La Tour Eiffel  
- Le Louvre  
- L’Arc de Triomphe  
- Notre-Dame  
- Montmartre  
Souhaites-tu un exemple de planning de visite ?
- Oui => planning
- Non merci => start

# transport
À Paris, tu peux utiliser :
- Le métro (rapide et pratique)
- Les bus
- Les vélos en libre-service (Vélib’)
Tu veux une info sur les tickets ?
- Oui => tickets
- Non => start

# restaurants
Quel type de cuisine cherches-tu ?
- Cuisine française => plats
- Végétarienne => vegetarien
- Pas chère => budget
- Retour => start

# meteo
En été, il fait souvent chaud (25-30°C).  
Au printemps et en automne, il fait doux (15-22°C).  
En hiver, il peut faire froid (5-10°C).  
- Retour => start

# planning
Voici un exemple pour 3 jours :
- Jour 1 : Tour Eiffel, balade sur la Seine  
- Jour 2 : Musée du Louvre, Jardin des Tuileries  
- Jour 3 : Montmartre et Sacré-Cœur  
- Retour => start

# tickets
Le ticket de métro s’appelle **Ticket t+**. Il coûte environ **2,10€**. Tu peux aussi acheter une **carte Navigo**.  
- Retour => start

# plats
Essaie ces plats typiques :
- Bœuf bourguignon
- Quiche lorraine
- Crêpes sucrées
- Fromages français
- Retour => start

# vegetarien
Voici quelques plats végétariens populaires :
- Ratatouille
- Salade niçoise (sans thon)
- Quiche aux légumes
- Falafel dans le quartier du Marais  
- Retour => start

# budget
Pour manger pas cher :
- Les boulangeries (sandwich + dessert)
- Les “formules midi” dans les brasseries
- Les restos étudiants ou fast-foods  
- Retour => start

# end
Merci ! Bon voyage à Paris et à bientôt !
