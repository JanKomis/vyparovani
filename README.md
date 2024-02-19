# Částečné vypaření směsi

<p>Program řeší výpočet částečného odpaření směsi benzenu a toulenu dle tohoto zadání:

<i>Směs benzenu a toulenu je přiváděna do výparníku, ve kterém se ohřívá na 50 °C. Tato směs je na vstupu tvořena 50% benzenem a 50% toulenem. Na výstupu výpary obsahují 68,4 % benzenu a kapalný zbytek obsahuje 40 % benzenu. Zbytek tvoří toulen. Jaké teplo je nutné průběžně dodávat do výparníku? Zanedbejte tlak na vstupu do výparníku.</i> </p>

<p> Kód je rozdělen do dvou Jupyter buněk. V první je řešen výpočet jednotlivých složek směsi na základě matice řešené knihovnou Numpy pomocí funkce linalg. Druhá počítá výsledné teplo nutné pro chod výparníku z měrných entalpií získaných knihovnou CoolProp pomocí funkce PropSI.</p>

<p>Program vznikl jako součást mé bakalářské práce (odkaz <a href="https://www.vut.cz/studenti/zav-prace/detail/116680">zde</a>) jež měl ukázat využití Pythonu pro technické výpočty konkrétně z pohledu procesního inženýrství.
Další programy z této práce:</p>

<ul>
    <li><a href="https://github.com/JanKomis/spalovaniJupyter/blob/main/README.md">Spalování zemního plynu</a></li>
    <li><a href="https://github.com/JanKomis/vypousteniNadrze">Tepelné ztráty</a></li>
    <li><a href="https://github.com/JanKomis/vyparnikH2O">Výparník H2O</a></li>
    <li><a href="https://www.vut.cz/studenti/zav-prace/detail/116680">Vypouštění nádrže</a></li>
</ul>

# Vytvořeno pomocí

<p align="left">
<a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/800px-Python-logo-notext.svg.png" width="36" height="36" alt="CSS3" /></a>
<a href="https://jupyter.org" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/640px-Jupyter_logo.svg.png" width="36" height="36" alt="Jupyter" /></a>
</p>
