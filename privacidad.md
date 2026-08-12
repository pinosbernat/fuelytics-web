---
title: Política de privacidad · Fueltic
---

# Política de Privacidad · Fueltic

**Última actualización:** 12 de agosto de 2026

---

## 1. Resumen

Fueltic es una aplicación para registrar repostajes y analizar el consumo de tus vehículos.

**Funciona íntegramente sin cuenta y sin conexión.** Si no creas una cuenta, tus datos no
salen nunca de tu dispositivo.

Si decides crear una cuenta para sincronizar entre dispositivos, tus datos se almacenan en
servidores situados en la **Unión Europea**.

---

## 2. Uso sin cuenta (modo predeterminado)

Al instalar la aplicación no se te pide ninguna cuenta. En este modo, todos los datos se
guardan **exclusivamente en el almacenamiento local de tu dispositivo**:

- Vehículos: nombre, matrícula, tipo de combustible, capacidad del depósito
- Repostajes: fecha, odómetro, litros, importe, moneda, gasolinera, notas
- Gasolineras: nombre, marca
- Preferencias: idioma, tema, moneda, unidades

**Nada de esto se transmite a ningún servidor. No podemos verlo.**

La única excepción, y por eso está aquí y no en la letra pequeña, son las **estadísticas de
uso anónimas** que se describen en el apartado 6: contadores del tipo «se ha abierto la app» o
«se ha creado un repostaje». **Nunca incluyen el contenido de la lista de arriba**: ni
matrículas, ni notas, ni importes, ni ubicaciones.

---

## 3. Uso con cuenta (opcional)

Si creas una cuenta, tratamos:

| Dato                                                  | Finalidad                                      | Base legal             |
| ----------------------------------------------------- | ---------------------------------------------- | ---------------------- |
| Dirección de correo electrónico                       | Identificarte y permitirte recuperar el acceso | Ejecución del contrato |
| Contraseña (cifrada)                                  | Autenticación                                  | Ejecución del contrato |
| Tus vehículos, repostajes, gasolineras y preferencias | Sincronizar entre tus dispositivos             | Ejecución del contrato |

### Si entras con Google

Puedes crear la cuenta o entrar **con tu cuenta de Google**, en lugar de con una contraseña. Si lo
haces, Google nos comunica **tu dirección de correo electrónico y tu nombre**. No pedimos ni
recibimos ningún otro dato de tu cuenta de Google: ni tus contactos, ni tu agenda, ni tu actividad.

El correo se usa para lo mismo que en el caso anterior —identificarte— y el nombre se usa
únicamente para identificarte ante las personas con las que compartas un vehículo (apartado
siguiente). Si no compartes ningún vehículo, no se muestra en ninguna pantalla.

**Si ese correo ya tenía cuenta en Fueltic, no se crea una segunda**: entrarás en la que ya
existía, que pasa a admitir las dos formas de acceso. Puedes ponerle una contraseña en cualquier
momento desde Ajustes → Perfil de usuario.

### Si compartes un vehículo

Puedes invitar a otras personas —hasta cinco en total— a un vehículo concreto, para llevar entre
todas el mismo cuaderno de repostajes. **Es la única función de Fueltic en la que tus datos son
visibles para otra persona, y siempre requiere que tú envíes la invitación.**

Cuando alguien acepta tu invitación:

- Esa persona ve **los repostajes, importes, gasolineras y notas de ese vehículo**, y puede
  **añadirlos y corregirlos**. **Borrar, solo los suyos**: los que registró otra persona únicamente
  los puede borrar quien creó el vehículo, que es además la única que puede eliminar el vehículo
  entero. Se comparte el vehículo, **no tu cuenta**: no ve tus otros
  vehículos, ni tus preferencias, ni ningún dato de tu perfil.
- Vosotros veis **cómo se llama** cada persona del vehículo, para saber quién registró cada
  repostaje. Ese nombre es el que Google nos comunicó o, si entraste con contraseña, **la parte de
  tu correo anterior a la arroba**. Nunca se muestra la dirección de correo completa.
- La invitación es **de un solo uso**, **caduca a las 24 horas** y puedes retirarla antes de que
  nadie la use.

Si creaste el vehículo puedes **sacar de él a cualquier persona** en cualquier momento; si te
invitaron, puedes **salir** cuando quieras. El acceso se corta de inmediato. Los repostajes ya registrados **se quedan en el vehículo**, porque el consumo
se calcula de un depósito lleno al siguiente y retirarlos falsearía las cifras de quienes se
quedan.

**Y si eliminas tu cuenta teniendo un vehículo compartido**, ese vehículo **no se destruye**: pasa a
la persona que lleva más tiempo en él, junto con el historial y las gasolineras que ese historial
usa. Tus repostajes se quedan ahí, **sin tu nombre**: quien los mire verá «otra persona». Es la
misma razón de siempre —el consumo se calcula de un lleno al siguiente, y borrarlos falsearía las
cifras de los demás—, y significa que **hay datos que registraste tú y que sobreviven a tu
borrado**, porque a partir de ese momento son de otra persona. Los vehículos que no compartes con
nadie sí se eliminan por completo.

Estos datos se almacenan en **Supabase** (infraestructura Postgres alojada en la Unión
Europea). El acceso está restringido por políticas de seguridad a nivel de fila: **solo tu cuenta
—y las personas que tú hayas invitado a un vehículo, para ese vehículo— pueden leer o modificar
esos datos**.

No vendemos, alquilamos ni cedemos tus datos a terceros. No los usamos para elaborar
perfiles ni para publicidad.

---

## 4. Tipos de cambio de divisa

Si registras repostajes en una moneda distinta del euro, la aplicación consulta la API
pública de **[Frankfurter](https://frankfurter.app)** (datos del Banco Central Europeo) para
obtener el tipo de cambio.

Esa consulta **solo transmite el código de la moneda** (por ejemplo, `USD`). No se envía
ningún dato personal, ni identificador, ni importe.

---

## 5. Publicidad

Fueltic puede mostrar publicidad a través de **Google AdMob**.

En el Espacio Económico Europeo, Reino Unido y Suiza se te solicitará tu consentimiento antes
de mostrar anuncios personalizados. Puedes **rechazarlo** y seguir usando la aplicación con
normalidad: verás anuncios no personalizados. Puedes cambiar tu elección en cualquier momento
desde los ajustes de la aplicación.

Google puede tratar datos según sus propias políticas:

- [Política de Privacidad de Google](https://policies.google.com/privacy)
- [Cómo usa Google los datos de sus socios](https://policies.google.com/technologies/partner-sites)

---

## 6. Estadísticas de uso

Para saber si la aplicación funciona y si resulta útil, registramos **un puñado de eventos
anónimos**: que se ha abierto la aplicación, que se ha completado la configuración inicial,
que se ha creado o editado un repostaje, y poco más.

**Qué se envía**

- El nombre del evento (por ejemplo, `repostaje.creado`)
- La fecha y hora
- Un **identificador aleatorio de instalación**, generado en tu dispositivo. No es el
  identificador de publicidad ni está relacionado con él, y no permite identificarte
- Ocasionalmente, un contador o un sí/no (por ejemplo, si el depósito se llenó del todo)

**Qué no se envía nunca**

Ni matrículas, ni notas, ni importes, ni kilómetros, ni ubicaciones, ni nada que hayas
escrito tú. La aplicación **descarta cualquier texto** antes de enviar, de modo que no es una
promesa sino una limitación técnica.

**Para qué sirve**

Solo para ver cifras agregadas: cuánta gente usa la aplicación y si vuelve a los pocos días.
**No creamos perfiles, no tomamos decisiones sobre ti y no vendemos ni compartimos estos datos
con nadie.** Se almacenan en la Unión Europea, junto al resto.

Si borras tu cuenta, los eventos asociados a ella se borran con ella.

---

## 7. Tus derechos

Conforme al RGPD, tienes derecho a:

- **Acceder** a tus datos — visibles en su totalidad dentro de la aplicación
- **Rectificarlos** — editables desde la aplicación
- **Suprimirlos** — ver §8
- **Portabilidad** — escríbenos y te enviamos una copia de tus datos en formato legible
- **Oponerte** al tratamiento y **retirar tu consentimiento** en cualquier momento

Para ejercerlos, escribe a **pibrstudios@gmail.com**. Responderemos en un plazo máximo de
30 días.

---

## 8. Eliminación de datos

**Sin cuenta**: desinstala la aplicación, o ve a Ajustes de Android → Aplicaciones →
Fueltic → Almacenamiento → Borrar datos. La eliminación es inmediata e irreversible.

**Con cuenta**: puedes eliminar tu cuenta y todos sus datos desde la propia aplicación, en
Ajustes → Perfil de usuario → Eliminar cuenta. También puedes solicitarlo escribiendo a
**pibrstudios@gmail.com**.

Al eliminar la cuenta se borran de forma permanente tu correo electrónico, tus credenciales y
todos tus vehículos, repostajes, gasolineras y preferencias almacenados en nuestros servidores.
**El borrado es inmediato**: ocurre en el momento, no en diferido, y **no es reversible**.

⚠️ **Con la excepción del apartado 3**: si compartías un vehículo, ese vehículo pasa a quien lleva
más tiempo en él —con su historial y las gasolineras que ese historial usa— y tus repostajes se
quedan ahí, sin tu nombre.

Si lo solicitas por correo en lugar de desde la app, lo ejecutamos en un plazo máximo de
30 días.

Los datos que tengas guardados localmente en el dispositivo permanecen ahí hasta que
desinstales la aplicación o borres sus datos.

---

## 9. Conservación

Conservamos tus datos mientras tu cuenta esté activa. Al eliminarla, se borran de inmediato
según lo descrito en §8. Las copias de seguridad de la infraestructura se rotan de forma
automática y ninguna sobrevive más de 30 días.

---

## 10. Servicios de terceros

| Servicio         | Finalidad                                                 | Política                                                                   |
| ---------------- | --------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Supabase**     | Autenticación, almacenamiento y estadísticas de uso (UE)  | [supabase.com/privacy](https://supabase.com/privacy)                       |
| **Google AdMob** | Publicidad                                                | [policies.google.com/privacy](https://policies.google.com/privacy)         |
| **Google Play**  | Distribución y pagos                                      | [policies.google.com/privacy](https://policies.google.com/privacy)         |
| **Resend**       | Envío del correo transaccional (confirmación, contraseña) | [resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy) |
| **Frankfurter**  | Tipos de cambio (sin datos personales)                    | [frankfurter.app](https://frankfurter.app)                                 |
| **Expo**         | Framework de la aplicación                                | [expo.dev/privacy](https://expo.dev/privacy)                               |

---

## 11. Menores

Fueltic está dirigida a personas adultas propietarias de vehículos. No recopilamos
conscientemente datos de menores de 16 años. Si crees que un menor nos ha facilitado datos,
escríbenos y los eliminaremos.

---

## 12. Cambios en esta política

Si modificamos esta política, actualizaremos la fecha de "última actualización". Si los
cambios afectan de forma sustancial al tratamiento de tus datos, te lo notificaremos dentro de
la aplicación antes de que entren en vigor.

---

## 13. Responsable del tratamiento y contacto

**PIBR Studios** — pibrstudios@gmail.com

Si consideras que no hemos tratado tus datos correctamente, puedes presentar una reclamación
ante la autoridad de control de tu país. En España, la
[Agencia Española de Protección de Datos](https://www.aepd.es).

---

<details>
<summary><strong>English version</strong></summary>

# Privacy Policy · Fueltic

**Last updated:** 12 August 2026

## 1. Summary

Fueltic records fuel-ups and analyses your vehicles' consumption.

**It works entirely without an account and offline.** If you do not create an account, your
data never leaves your device. If you create one to sync across devices, your data is stored
on servers located in the **European Union**.

## 2. Without an account (default)

No account is required. All data — vehicles, fuel-ups, stations and preferences — is stored
**only in your device's local storage**. None of it is ever transmitted and we cannot see it.

The one exception, stated here rather than in the small print, is the **anonymous usage
statistics** described in section 6: counters such as "the app was opened" or "a fuel-up was
created". They **never include any of the content above** — no plates, notes, amounts or
locations.

## 3. With an account (optional)

If you create an account we process your **email address**, an **encrypted password**, and
your **vehicles, fuel-ups, stations and preferences**, for the sole purpose of syncing across
your devices. Legal basis: performance of the contract.

**If you sign in with Google**, Google shares your **email address and name** with us — nothing
else: no contacts, no calendar, no activity. The email is used to identify you; the name is used
only to identify you to people you share a vehicle with (below), and is shown nowhere if you share
none. If that email already had a Fueltic account, **no second account is created**: you sign in
to the existing one, which then accepts both ways in. You can set a password for it at any time
from Settings → User profile.

**If you share a vehicle**, you can invite other people — five in total at most — to one specific
vehicle, so that you all keep the same fuel log. This is the only feature in Fueltic where your
data becomes visible to someone else, and it always requires you to send the invitation. Whoever
accepts sees **the fuel-ups, amounts, stations and notes of that vehicle**, and can add, correct
and correct them — but **delete only their own**: fuel-ups logged by someone else can only be
deleted by whoever created the vehicle, who is also the only person who can delete the vehicle
itself. They do not see your other vehicles, your preferences or anything from your
profile. You each see **the name** of the other people in the vehicle, so you know who logged
what: that name is the one Google gave us or, if you signed up with a password, **the part of your
email before the @** — the full address is never shown. Invitations are **single-use**, **expire
after 24 hours**, and can be revoked before anyone uses them. You can remove anyone from the
vehicle, or leave it yourself, at any time; access stops immediately. Fuel-ups already logged
**stay with the vehicle**, because consumption is measured from one full tank to the next and
removing them would falsify the figures for whoever stays.

**And if you delete your account while sharing a vehicle**, that vehicle **is not destroyed**: it
passes to whoever has been in it the longest, together with its history and the stations that
history uses. Your fuel-ups stay there **without your name** — anyone looking will see "someone
else". Same reason as always, and it means **some data you logged survives your deletion**, because
from that moment it belongs to someone else. Vehicles you share with nobody are deleted in full.

Data is stored on **Supabase** (Postgres infrastructure hosted in the EU). Row-level security
policies ensure **only your account — and the people you invited to a vehicle, for that
vehicle — can read or modify that data**.

We do not sell, rent or share your data with third parties, and we do not use it for
profiling or advertising.

## 4. Currency exchange rates

For fuel-ups in a currency other than the euro, the app queries the public
**[Frankfurter](https://frankfurter.app)** API (European Central Bank data). Only the currency
code is transmitted — no personal data, identifiers or amounts.

## 5. Advertising

Fueltic may show ads via **Google AdMob**. In the EEA, UK and Switzerland you will be asked
for consent before personalised ads are shown. You may **decline** and continue using the app
normally with non-personalised ads, and change your choice at any time in the app's settings.

## 6. Usage statistics

To know whether the app works and is useful, we record **a handful of anonymous events**: that
the app was opened, that setup was completed, that a fuel-up was created or edited, little else.

**What is sent**: the event name, the date and time, a **random installation identifier**
generated on your device — not the advertising ID, unrelated to it, and unable to identify you
— and occasionally a counter or a yes/no.

**What is never sent**: no plates, notes, amounts, distances, locations or anything you typed.
The app **discards any text** before sending, so this is a technical limitation rather than a
promise.

We only look at aggregate figures: how many people use the app and whether they come back.
**We do not build profiles, make decisions about you, or sell or share this data.** It is
stored in the European Union. If you delete your account, the events linked to it go with it.

## 7. Your rights

Under the GDPR you may access, rectify, erase, port and object to the processing of your data,
and withdraw consent at any time. For portability, email us and we will send you a copy of your
data in a readable format. Contact **pibrstudios@gmail.com**; we respond within 30 days.

## 8. Deleting your data

**Without an account**: uninstall the app, or Android Settings → Apps → Fueltic → Storage →
Clear data. Immediate and irreversible.

**With an account**: delete your account and all its data from within the app, under
Settings → User profile → Delete account, or by emailing **pibrstudios@gmail.com**. This permanently erases
your email, credentials and all vehicles, fuel-ups, stations and preferences from our servers.
Deletion from within the app is **immediate**, not deferred, and cannot be undone. Requests by
email are carried out within 30 days.

## 9. Retention

We retain your data while your account is active. Deleted accounts are erased immediately as
described in §8. Infrastructure backups rotate automatically and none survives beyond 30 days.

## 10. Third-party services

Supabase (authentication and storage, EU) · Resend (transactional email) · Google AdMob (advertising) · Google Play
(distribution and payments) · Frankfurter (exchange rates, no personal data) · Expo
(application framework).

## 11. Children

Fueltic is intended for adult vehicle owners. We do not knowingly collect data from anyone
under 16. Contact us if you believe a minor has provided us with data and we will delete it.

## 12. Changes

We will update the "last updated" date. Material changes will be notified in-app before taking
effect.

## 13. Controller and contact

**PIBR Studios** — pibrstudios@gmail.com

You may lodge a complaint with your national supervisory authority. In Spain, the
[Spanish Data Protection Agency](https://www.aepd.es).

</details>
