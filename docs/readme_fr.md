
<h2 align='center'>
Salut! Bienvenue dans mon monde :alien:
</h2>
<p align="center">
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português</a>
    ·
    <a href="/docs/readme_en.md">English</a>
    <br><br>
        Sorry my mistakes, I'm just starting to learn French :)

  </p>
</p>


<p align='center'>
<a href="https://dev.to/adelbs"><img height="30" src="https://raw.githubusercontent.com/adelbs/adelbs/main/icons/dev.png"></a>&nbsp;&nbsp;
<a href="https://instagram.com/felipisses"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/instagram.png?raw=true"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/felipejacob/"><img height="30" src="https://github.com/adelbs/adelbs/blob/main/icons/linkedin.png?raw=true"></a>
</p>


``` javascript

const Nerd = _=> {};
const Overlander = _=> {};

function Felipe() {
    try {
        Nerd.call(this);
        Overlander.call(this);
        CommonPerson.call(this); 
    } 
    catch(x) {
        console.log('Certainement pas une personne normale...);
    }

    this.name = 'Felipe';
    this.personality = [
        `J'utilise des points-virgules dans JS`, 
        `Tuba toujours tourné vers l'avant`, 
        `Café sans sucre, s'il vous plaît`,
        `Rêveur`];

    this.currentMission = 'Essayer de refactoriser le monde';
} 

console.log(new Felipe());
