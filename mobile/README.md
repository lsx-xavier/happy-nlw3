# Ferramentas

- Expo = Varias funcionalidades de dentro do mobile, meio prontas so para utilizar (galeria de fotos, calendario, notificações push, geolocalização...), uma das vantagens de usar o expo é nao precisar usar nenhuma SDK dos sistemas, basta abrir o expo no celular e rodar a aplicação;
- @expo-google-fonts = Usar as fonts já do google fonts;
- React navigation = Instalado para usar algumas funcionalidades de navegação como:
  - Stack => Navegação em pilha, geralmente navegação com buttons;
  - Tab Navigation => Navegação em abas, encima e embaixo de exemplo;
  - Drawer navigation => Menu na lateral, estilo google;
- Deep link = Usando o "Linking.openURL('X')" do react-native. Ele faz navegar de um APP para outro;
- Expo Image Picker = Pegar permissões de acesso a galeria e a camera, com isso podemos subir imagens no cadstro;

# Anotações (estudos 📑)

- React Native = Antigamente tinhamos que programar com as linguagens nativas de cada sistema (iOS e Android) o React Native veio para melhorar essa forma gerando 1 lingaugem para os 2 sistemas, ganho em produtividade (colocar a aplicação mais rapida no ar) e na manutenção;
- Metro Bundler = Pega todos os arquivos javascript e tranforma no bundle.js, o bundle.js é usado para fazer o JS Core;
- Js Core = Faz com que os celulares comecem a entender javascript;
- ReactJs != React Native = Muda os elementos que usamos em tela e a estilização( View = div, section, main | Text= p, h1, span, strong) nao usamos id, class... usamos apenas style com StyleSheet e nao temos heranças de estilos;
- ScrollView = Serve para exatamente o que a tag diz, fazer scroll na tela inteira;
  - Propridades do ScollView:
    - horizontal = Faz com que o Scroll seja na horizontal e não na vertical como padrão;
    - pagingEnabled = Faz com que o Scroll seja completo, impede dele ficar com o Scroll no meio do caminho;
- TextInput = input do html;
  - Propriedade -> TextInput = textarea do html;
- Switch = checkbox do html;
- Emulador no computador = Se tiver rodando o app no computador, temos que fazer "adb reverse tcp:33333 tcp:33333" para conseguir acessar a api com baseURL: 'http://localhost:33333' ;
- Expo Image Picker anotções (ImagePicker = todas as funções de expo-image-picker):
  - ImagePicker.requestCameraRollPermissionsAsync() = Busca a liberação do acesso a camera e galeria;
  ```js
    ImagePicker.launchImageLibraryAsync({
      allowsEditing: true, // Permite o usuário a cropar e editar a foto;
      quality: 1, // Qualidade da foto
      mediaTypes: ImagePicker.MediaTypeOptions.Images, // Permite apenas as imagens
    });
  ```


# Entrar em contato!

<a href="https://www.linkedin.com/in/lucas-xavier-588b67a6/" target="_blank" >
  <img alt="Linkedin - Lucas Xavier" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>&nbsp;&nbsp;&nbsp;
<a href="mailto:ls.xxavier@gmail.com" target="_blank" >
  <img alt="Email - Lucas Xavier" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
</a> 

Lucas Xavier