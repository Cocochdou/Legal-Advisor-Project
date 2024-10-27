# Legal Advisor Assistant LLM project
Our group will create and model a specific LLM assistant about french laws. Our assistant will follow these requirements:

## *LLM Criteria*
 The assistant should be easy to use and navigate.
 The assistant must provide accurate and reliable legal information.
 The assistant must communicate legal concepts in a clear and simple manner.
 The assistant must not provide legal advises and specify that it can hallucinate and be wrong. 
 Maintaining up-to-date answers.
 
## Type of Q&A the assistant should be able to answer
### Specific law enunciation
Q quel est l'article 131-21-1 du code pénal français ? 
R Lorsqu'elle est encourue comme peine complémentaire, la confiscation d'un animal ou d'une catégorie d'animal
concerne l'animal qui a été utilisé pour commettre ou tenter de commettre l'infraction ou à l'encontre duquel
l'infraction a été commise.
Elle concerne également les animaux dont le condamné est propriétaire ou dont il a la libre disposition, si ces
animaux étaient susceptibles d'être utilisés pour commettre l'infraction ou si l'infraction aurait pu être commise
à leur encontre.
La juridiction qui prononce la confiscation de l'animal prévoit qu'il sera remis à une fondation ou à une
association de protection animale reconnue d'utilité publique ou déclarée, qui pourra librement en disposer.
Si l'animal n'a pas été placé en cours de procédure, le condamné doit, sur injonction qui lui est faite par le
ministère public, le remettre à l'organisme visé à l'alinéa précédent. Les dispositions du cinquième alinéa de
l'article 131-21 sont également applicables.
Lorsque l'animal a été placé en cours de procédure, la juridiction qui ordonne sa confiscation peut mettre les
frais de placement à la charge du condamné.
p.27 Code pénal
Partie législative - Livre Ier : Dispositions générales - Titre III : Des peines
Lorsqu'il s'agit d'un animal dangereux, la juridiction peut ordonner qu'il soit procédé à son euthanasie, le cas
échéant aux frais du condamné.

Q Peux-tu me citer les articles du Code Pénal concernant les homicides involontaires?
R Les homicides involontaires sont régis par plusieurs articles du Code pénal. Ils concernent les situations où une personne provoque la mort d'une autre sans avoir eu l'intention de la tuer. 
Article 221-6 : Cet article prévoit que le fait de causer, par imprudence, négligence ou manquement à une obligation de sécurité ou de prudence, la mort d'autrui constitue un homicide involontaire. La peine encourue est de 3 ans d'emprisonnement et 45 000 euros d'amende.
Article 221-6-1 : Cet article traite des homicides involontaires commis dans le cadre d'une activité professionnelle. La peine est aggravée : 5 ans d'emprisonnement et 75 000 euros d'amende.
Article 221-7 : Les peines peuvent être plus lourdes si certaines circonstances aggravantes sont présentes, comme la violation d'une obligation spécifique de sécurité ou l'état d'ivresse.

Q Cite moi l'article parlant de la rébellion armée 
R 433-8 La rébellion armée est punie de cinq ans d'emprisonnement et de 75 000 euros d'amende.
La rébellion armée commise en réunion est punie de dix ans d'emprisonnement et de 150 000 euros d'amende.

Q Quelles sont les autres infractions de 4ème classe ? 
R Usage d´un téléphone tenu en main ; Circulation sur la bande d´arrêt d´urgence ; Conduite sans ceinture de sécurité ; Refus de priorité ; Non-respect d´un feu rouge ou d´un stop ; Franchissement ou chevauchement d´une ligne continue ; Absence de visite technique périodique ; Conduite en état alcoolique ; Circulation en sens interdit ; Non respect de la distance de sécurité ; Excès de vitesse inférieur à 50 km/h ; Dépassement dangereux ; Circulation sans éclairage ; Absence de certificat d´immatriculation.

### Real life cases

Q Qu'est-ce que je risque si je me trompe dans ma déclaration d'impôts?
R Si vous faites une erreur dans votre déclaration d'impôts, les sanctions dépendent de la nature de l'erreur (volontaire ou non) et de la rapidité avec laquelle vous la rectifiez.
Erreur involontaire : Si vous avez fait une erreur de bonne foi, vous pouvez la corriger en ligne via votre espace personnel dans les 3 ans suivant la déclaration. Vous ne serez pas pénalisé si l'erreur est rectifiée avant un contrôle fiscal.
Omission ou fausse déclaration : Si l'administration fiscale détecte une erreur ou omission après un contrôle, vous risquez une pénalité :
10% de majoration en cas de simple oubli.
40% de majoration en cas d'absence de correction ou d'erreur volontaire.
80% de majoration en cas de fraude avérée.
En plus des pénalités, des intérêts de retard de 0,20 % par mois s'ajoutent aux impôts non payés.

Q Que puis-je faire si un chien s'est échappé de chez lui et m'a mordu ? Puis-je porter plainte ? 
R Si un chien s'échappe de chez son propriétaire et vous mord, vous avez le droit de prendre plusieurs actions :
Déclaration à la police ou à la gendarmerie : Vous pouvez déposer plainte pour blessures involontaires si le propriétaire du chien a fait preuve de négligence. Cela peut conduire à une enquête pour établir la responsabilité.
Signalement à la mairie : Le maire peut prendre des mesures contre le propriétaire, telles que la mise sous surveillance du chien ou la demande de certificat vétérinaire.
Procédure civile : Vous pouvez également entamer une procédure civile pour demander une indemnisation des dommages subis (frais médicaux, préjudice moral, etc.).
Responsabilité civile du propriétaire : En vertu de l'article 1243 du Code civil, le propriétaire d'un animal est responsable des dommages causés par celui-ci. Vous pouvez donc exiger réparation de la part du propriétaire.

Q J'ai une injonction d'éloignement contre quelqu'un. Qu'est-ce que je risque si je l'enfreins ?
R Si vous avez une injonction d'éloignement (souvent appelée "ordonnance de protection") contre quelqu'un et que vous l'enfreignez, cela peut entraîner des conséquences graves. Violation de l'injonction : Si vous enfreignez une injonction d'éloignement, vous pouvez être poursuivi pour délit de non-respect d'une décision de justice, prévu par l'article 227-4-2 du Code pénal. Cela peut entraîner : Jusqu'à 2 ans de prison.30 000 euros d'amende.Récidive : Si vous récidivez, les peines peuvent être aggravées. En résumé, il est important de respecter les termes de l'injonction, car toute violation peut entraîner des sanctions pénales.

### Answer to tests
Q La XXXXX est le fait, sans autorisation ou déclaration régulière, d'offrir, de mettre en vente ou
d'exposer en vue de la vente des biens ou d'exercer toute autre profession dans les lieux publics en violation
des dispositions réglementaires sur la police de ces lieux.
La XXXX est punie de six mois d'emprisonnement et de 3 750 € d'amende.
Que représente le XXXX ici ?
R La vente à la sauvette

### Really precise and specific questions
Q Combien de classes d'infraction au code de la route existe-t-il ? 
R Il existe 5 classes d'infraction au code de la route 
Q De combien serait mon amende pour avoir grillé un feu rouge ?
R Pour avoir grillé un feu (contravention de 4ème classe) vous risquez jusqu'à 750 € d'amende
Q Et si mon amende est forfaitaire ? (prix normal non majoré)
R 135€
Q Et si elle est minorée ? (payée sous les 15 jours) 
R 90€

### Specificity of not giving advice
Q Que penses-tu de la peine de mort ?
R Je n'ai pas d'avis

### Capacity to maintain a coherent and relevant conversation about a specific subject
Q J'ai reçu une amende pour avoir grillé un feu rouge, combien de temps ai-je pour payer ?
R 45 jours
Q Puis-je minorer mon amende en payant plus rapidement ? 
R Oui si sous 15 jours
Q Que se passe-t-il si je ne paye pas à temps ? (sous 45 jours)
R L'amende est majorée si payée après plus de 45 jours, possibilité que le Trésor public engage une procédure de recouvrement forcé
Q Puis-je contester mon amende ?
R La contestation n'est recevable qu'à la condition d'être adressée par le contrevenant désigné sur l'avis de contravention (titulaire du certificat d'immatriculation, locataire ou acquéreur).
Q Combien de temps ai-je ?
R Vous disposez d'un délai de 45 jours à partir de la date d'envoi de l'avis de contravention pour envoyer votre requête.
Q Quelle procédure suivre ?
R Avant de formuler votre requête, vous pouvez demander la photographie de l'infraction. Cette démarche peut être utile notamment en cas de vol de plaques d'immatriculation ou lorsqu'il y a un doute sur le conducteur qui a commis l'infraction. La demande de photo ne suspend pas les délais de recours contre l'avis de contravention. Il est donc préférable de réclamer le cliché en parallèle de la contestation.
