# Draftd · legal

Las páginas legales de [Draftd](https://github.com/LightSideStudio/draftd), la aplicación de
fútbol fantasy de LightSide Studio.

- [Política de privacidad](https://lightsidestudio.github.io/draftd-web/privacidad.html)
- [Términos y condiciones](https://lightsidestudio.github.io/draftd-web/terminos.html)
- [Licencias de software libre](https://lightsidestudio.github.io/draftd-web/licencias.html)

## No se edita a mano

Estos HTML **se generan** desde el repositorio de la aplicación, donde vive el texto
(`src/legal/documentos.ts`). Ahí es donde hay que cambiar cualquier cosa:

```bash
npm run legal:web    # regenera docs/
```

y desde ahí se copia aquí. El motivo de que sea así: la app enseña los mismos documentos en
Ajustes → Legal, y si fuesen dos textos separados acabarían diciendo cosas distintas — el que
se queda viejo es siempre el de la app, que nadie mira.

## Por qué un repositorio aparte

GitHub Pages no funciona en repositorios privados con plan gratuito, y el de la aplicación
tiene que seguir privado. Aquí sólo hay HTML público.

Contacto: info@draftd.com
