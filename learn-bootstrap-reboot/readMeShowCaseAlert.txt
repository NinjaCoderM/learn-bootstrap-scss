.alert.alert-danger>p{Text Text}
im Text a.alert-link für passende Links
.alert.alert-danger>(h4{Warning} + hr + p{Text Text})   --> sieht gut aus
https://icons.getbootstrap.com/
    Bootstrap Icons verwenden mit install i bootstrap-icons, wird später gezeigt
    oder ohne statt Icon font (nur mit install i bootstrap-icons) 'Copy html' kopieren und einfügen
    Beispiel (width="16" height="16" anpassen, damit zu Text passt):
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-exclamation-triangle" viewBox="0 0 16 16">
        <path d="M7.938 2.016A.13.13 0 0 1 8.002 2a.13.13 0 0 1 .063.016.15.15 0 0 1 .054.057l6.857 11.667c.036.06.035.124.002.183a.2.2 0 0 1-.054.06.1.1 0 0 1-.066.017H1.146a.1.1 0 0 1-.066-.017.2.2 0 0 1-.054-.06.18.18 0 0 1 .002-.183L7.884 2.073a.15.15 0 0 1 .054-.057m1.044-.45a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767z"/>
        <path d="M7.002 12a1 1 0 1 1 2 0 1 1 0 0 1-2 0M7.1 5.995a.905.905 0 1 1 1.8 0l-.35 3.507a.552.552 0 0 1-1.1 0z"/>
    </svg>

Closeable
.alert.alert-danger.alert-dismissible.fade.show>(h4{Warning} + hr + p{Text Text} + button.btn-close[type=button data-bs-dismiss="alert"]) 
                                                --> Attribut data-bs-dismiss="alert" in button um close zu ermöglichen
                                                --> .alert-dismissible.fade.show für x rechts oben

