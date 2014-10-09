# Présentation {#param-inline-help:9d124f01-e159-4f18-91b6-4bfec7f937bf}


## Principe et fonctionnement général {#param-inline-help:e6d1fe33-57a9-471b-ab1d-b087957a988e}

Dynacase propose des mécanismes d'aide en ligne. Ils permettent, depuis les interfaces standards
des documents, de proposer à l'utilisateur un accès direct à une documentation d'aide.

Les documents d'aide en ligne sont stockés dans dynacase et par conséquent sont modifiables
directement depuis les interfaces WEB dynacase par les personnes habilitées.

Les documents d'aides peuvent être traduits en plusieurs langues. L'interface de consultation
propose par défaut les traductions pour la langue d'utilisation de dynacase (si elles existent)
et donne la possibilité à l'utilisateur d'accéder aux autres traductions disponibles.

Un document d'aide est composée de rubriques, chacune des rubriques est traduisible individuellement.


## Utilisation {#param-inline-help:72ffbd1b-d431-41b5-b46b-124d4f2868b4}

Un document d'aide en ligne peut être lié à une famille. Dans ce cas il est accessible via le
lien d'aide sur l'attribut dans l'édition d'un document de cette famille.

Soit il s'agit d'un document d'aide non lié à une famille et il peut être accédé en consultation
comme tout document dynacase.

Les documents d'aide en ligne ont des vues de consultation et d'édition spécifiques afin de faciliter
la lecture et la saisie.

![Aide présentée en lecture](1000020100000344000001EEB9D8264F.png)

![Aide présentée en écriture](100002010000032D00000247062A418A.png)

Il est possible de mettre des liens vers des documents d'aide en ligne, qu'ils soient liés ou non à une famille, via une syntaxe [ADOC aide] ou [ADOC aide#rubrique]

