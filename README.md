flat_auth changes:
- install https://www.drupal.org/project/authtoken/releases/7.x-1.1 and enable it
- git clone git@github.com:ibrahimab/flat_auth inside flat_deposit module and enable it
- clone git@github.com:thelanguagearchive/flat_encryption branch "feature/flat_auth" and run "mvn clean install -U" to get the latest jar
- clone git@github.com:thelanguagearchive/flat_decryption branch "feature/flat_auth" and run "mvn clean install -U" to get the latest jar
- apply all the file changes in this commit
- flat_encryption branch "feature/flat_auth" also has several docker adjustments, including the flat_auth plugin, see that folder for its readme
