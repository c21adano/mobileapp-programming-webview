
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

Skapade en web app med en extern och en intern webview.
Började med att lägga till webview element i content_main. sen ändrades webviews id till my_webview
La till denna koden till oncreate:

```
AdamsWebView = findViewById(R.id.my_webview);
AdamsWebView.setWebViewClient(new WebViewClient());
WebSettings webSettings = AdamsWebView.getSettings();
webSettings.setJavaScriptEnabled(true);
```

Skapade en local html file som används för internal webview
Länkar den locala html filen till när internal web knappen blir tryckt
länkar his.se när external web lnappen blir tryckt.


hur appen ser ut när den startar.
![](Screenshot_webviewjuststarted.png)

den external webviewen
![](Screenshot_externalweb.png)

den internal webviewen
![](Screenshot_internalweb.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
