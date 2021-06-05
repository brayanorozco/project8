## Pré-requis pour se connecter

Il vous faut créer votre premier utilisateur afin de pouvoir vous connecter à l'interface.
Voici les étapes :

1. Ouvrez votre terminal ou votre invite de commande et tapez `mongo` puis appuyez sur entrer.
2. Tapez `use projet10` puis appuyez sur entrer.
2. Tapez `db.users.insert({email: "myEmail", password: "myPwd"})` en remplaçant myEmail par l'email de votre choix ainsi que myPwd par le mot de passe que vous souhaitez puis appuyez sur entrer.

____________________________________________________________id
Regarding ticket management, we’d like to have a sort of administrator
user who will be able to assign a ticket to other users.

For management reasons we don’t want that right to be given to all employees.
So any regular (non-administrator) user should not be able to attribute a ticket to somebody else.
Also, ideally, we would be able to filter tickets according to whether or not someone has been assigned
to them.We would also like to track ticket creators (keeping in mind thatany user should be able to 
create a ticket). What would be great would be to find on the details page of a ticket the email 
address of its creator, in order to contact them quickly in case of query.

This is because a user won’t necessarily work on a ticket after creating it.
So if a user creates a ticket, and the administrator attributes it to someone who is not
the creator itself, then if that someone needs additional information to process the ticket
they’ll need to contact the creator quickly. My team also told me that I need to comment on
tickets in order to speed up the exchange of information and thus the speed of processing.

Regarding the tickets listing, there seems to be a display problem with the list: it doesn't show
the title attributed to a ticket but what seems to be an ID number. For readability reasons, we want
to see the title instead of this number. Also for readability reasons, can you display an image or an
icon on the list that indicates the status of the ticket (processed or unprocessed)?

This will allow our teams to be more efficient when processing tickets.
0___________________________________________________________