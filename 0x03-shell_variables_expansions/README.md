0x03-shell_variables_expansions

Créez un script qui affiche "hello user", où "user" est l'utilisateur actuel de Linux.
Solution :
1. Créez un fichier nommé `hello_user.sh`.
2. Ajoutez le contenu suivant dans le fichier :
   ```bash
   #!/bin/bash
   echo "hello $(whoami)"

