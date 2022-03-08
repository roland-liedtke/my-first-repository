<h1>
  <a href="https://git-scm.com/">
    git
  </a>
   - system kontroli wersji
</h1>

<ol>
  <li>
    Przejdź do katalogu projektu i wykonaj w Terminalu polecenie:
    <pre>$ git init</pre>
  </li>
  <li>
    Aby rozpocząć kontrolę wersji lokalnej dodajemy pliki, licencję i pierwszy commit (znajdzie się w poczekalni):
    <pre>$ git add *</pre>
    <pre>$ git add LICENSE</pre>
    <pre>$ git commit -m 'first commit'</pre>
  </li>
  <li>
    Jeśli chcesz pobrać istniejące repozytorium wpisz:
  <pre>$ git clone https://github.com/userName/repoName</pre>
  </li>
  <li>
    Podstawowym narzędziem do sprawdzania stanu plików jest:
    <pre>$ git status</pre>
  </li>
  <li>
    Następnie potwierdzamy zmiany stosując:
    <pre>$ git commit -m "This commit will..."</pre>
  </li>
  <li>
    Aby wyświetlić zdalne repozytoria przejdź do katalogu lokalnego i wykonaj polecenie:
    <pre>$ git remote -v</pre>
  </li>
  <li>
    Aby dodać zdalne repozytorium należy wpisać:
    <pre>$ git remote add [skrót] [url]:</pre>
  </li>
</ol>

<footer>
  <p>Źródło</p>
  <a href="https://git-scm.com/">
    git
  </a>
</footer>
