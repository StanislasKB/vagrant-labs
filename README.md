# Vagrant-labs
## Lab 1
> Tâches
>
>> - Initialiser vagrant
>> - Démarrer la VM
>> - Se connecter en SSH
>> - Arrêter la VM
>> - Supprimer la VM
>
>Commandes 
>
>> - vagrant init
>> - vagrant up
>> - vagrant ssh
>>      - Mot de passe par défaut = vagrant
>> - vagrant halt
>> - vagrant destroy

## Lab 2
> Tâches
>
>> - Initialiser vagrant
>> - Démarrer la VM
>> - Se connecter en SSH
>> - Installer nginx
>> - Démarrer nginx et activer son démarrage au lancement de la VM
>> - Créer une vbox avec cette VM
>> - Publier la vbox sur vagrant cloud
>
>Commandes 
>
>> - vagrant init (--box-version)
>> - vagrant up
>> - vagrant ssh
>>      - Mot de passe par défaut = vagrant
>>  - vagrant package --output nginx_box
>> - vagrant halt
>> - vagrant destroy