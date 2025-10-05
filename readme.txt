Para Fazer com que os apps não aparecam na lista do wofi inclua "Hidden=true" em /usr/share/applications/{class do app}.desktop.
Se você não sabe qual a "class" do app, abra-o e digite em um terminal: "hyprctl clients" e veja a class no app desejado.

Caso queira mudar o nome desse app no wofi, edite esse {class}.desktop e procure por algo do tipo "GNOME-NAME-..." e altere para o nome desejado, se não tiver esse atributo busque por "Name" ou alguma coisa parecida.
Caso queira fazer o app aparecer como um app apenas ao invés de varias ações, busque por actions e apague esse atributo.
