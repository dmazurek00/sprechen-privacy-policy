# Datenschutzerklärung – DTB B2 Sprechen

**Stand:** 2026-10-07

## Überblick

Sprechen (DTB B2 Sprechen) ist eine Anwendung zum Üben der mündlichen Prüfung „Deutsch-Test für den
Beruf B2". Sie führt ein simuliertes Prüfungsgespräch mit einer KI-Prüferin und bewertet die Leistung
anschließend. Es gibt sie in zwei Formen: als **Web-App** im Browser unter `sprechen.deutsch.quest`
und als **Android-App**. Beide nutzen denselben Server und verarbeiten deine Daten auf dieselbe Weise;
Unterschiede bei der Speicherung auf deinem Gerät stehen im Abschnitt „Auf deinem Gerät".

Der Zugang wird persönlich vergeben (Testzugang). Sprechen ist kein offizielles Prüfungsangebot; die
KI-Bewertung dient dem Üben.

**Verantwortlich im Sinne der DSGVO:** Dawid Mazurek
**Kontakt:** derdavid@deutsch.quest
**Postanschrift:** im [Impressum von Sprechen](https://sprechen.deutsch.quest/zugang/?lang=de&legal=imprint)

Für Anfragen über das Formular unter [sprechen.deutsch.quest/zugang](https://sprechen.deutsch.quest/zugang/)
gelten die dort verlinkten Datenschutzhinweise.

## Welche Daten verarbeitet werden

- **Tonaufnahme deiner Stimme** während des Prüfungsgesprächs, bis zu 20 Minuten pro Gespräch.
  Umgebungsgeräusche können mit aufgenommen werden.
- **Text des Gesprächs** (Transkript) und die dir gestellten Prüfungsaufgaben.
- **Bewertungsergebnis** deiner Prüfung.
- **Problemmeldungen**, die du selbst aus der Anwendung schickst („Problem mit diesem Gespräch melden"):
  der gewählte Grund, dein optionaler Text und die Nummer der Sitzung.
- **Rückmeldung zur Testversion** (Umfrage in der Anwendung): deine Antworten, zugeordnet zu deinem
  Benutzerkonto und gegebenenfalls der betreffenden Prüfung.
- **Freiwillige Ausspracheübung** nach der Prüfung: eine kurze Aufnahme (10 bis 90 Sekunden), die du selbst mit
  „Analysieren" über unseren Server an Google sendest; auf unserem Server wird sie nicht gespeichert.
- **Technische Daten der Sitzung** zur Fehlersuche: Verbindungsqualität, Unterbrechungen, Typ und
  Version von Browser bzw. Gerät sowie die Version der Anwendung.
- **Zugangsdaten zu deinem Profil**: Adresse des Profils, Benutzername (bei Testzugängen dein Vorname)
  und Passwort.

Es werden **keine** Werbe-, Analyse- oder Tracking-Werkzeuge eingesetzt, es werden keine Cookies
gesetzt und es findet keine Profilbildung statt.

## Wer die Daten verarbeitet

Die Anwendung kennt **keine API-Schlüssel**. Sie spricht ausschließlich mit dem Server von Sprechen;
dieser setzt die Schlüssel ein und leitet weiter:

| Empfänger | Was er erhält | Wozu |
|---|---|---|
| Server von Sprechen (`sprechen.deutsch.quest`), betrieben bei Exoscale in Sofia, Bulgarien (EU) | Tonaufnahme, Transkript, Ergebnis, technische Daten, Zugangsname | Speicherung, Auswertung, Anzeige des Ergebnisses |
| Google (Gemini) | Ton des laufenden Gesprächs; danach die Tonaufnahme | Gespräch mit der Prüferin; neues Transkript und Bewertung der Aussprache |
| Anthropic (Claude) | **ausschließlich Text** — Transkript und Prüfungsaufgaben | Erstellen der Aufgaben, sprachliche und inhaltliche Bewertung |

**An Anthropic gelangt kein Ton.** Problemmeldungen aus der Anwendung gehen per E-Mail über Resend (Versand)
und Porkbun (Weiterleitung) in das Gmail-Postfach des Betreibers (Google); auf dem Server von Sprechen werden
sie nicht zusätzlich als Datei gespeichert. Die Antworten der Umfrage speichert nur der Server von Sprechen.
Darüber hinaus findet keine Weitergabe an Dritte statt.

Beim Gespräch (Google) und beim Erstellen der Aufgaben (Anthropic) leitet unser Server die Anfragen deines Browsers
weiter; dabei können technische Angaben wie deine IP-Adresse und der Browsertyp mitgehen.

**Übermittlung in die USA.** Google und Anthropic verarbeiten die Daten auch in den USA; für Problemmeldungen
per E-Mail gilt dasselbe für Resend, Porkbun und Google (Gmail). Grundlage sind
die Standardvertragsklauseln der EU-Kommission und, soweit der Anbieter zertifiziert ist, der
Datenschutzrahmen EU-USA (EU-US Data Privacy Framework). Beide Anbieter verarbeiten die Daten im Auftrag nach ihren Bedingungen für die
Programmierschnittstelle; danach werden die Inhalte nicht zum Training ihrer Sprachmodelle (Gemini, Claude) verwendet.
Einzelheiten: [Datenschutzerklärung von Google](https://policies.google.com/privacy),
[Nutzungsbedingungen der Gemini API](https://ai.google.dev/gemini-api/terms),
[Datenschutzerklärung von Anthropic](https://www.anthropic.com/privacy).

## Einwilligung und Rechtsgrundlagen

Die Aufnahme und ihre Verarbeitung erfolgen nur mit deiner ausdrücklichen **Einwilligung**
(Art. 6 Abs. 1 lit. a DSGVO), die du vor jedem Gespräch auf dem Bildschirm „Vorbereitung" erteilst.
In der Web-App wählst du dort zwischen der Aufnahme mit Auswertung und einer nur lokalen
Sicherheitskopie. Du kannst die Einwilligung dort jederzeit abwählen und sie jederzeit für die Zukunft
widerrufen. Ohne diese Einwilligung wird keine Tonaufnahme hochgeladen. Das Gespräch selbst läuft
weiterhin über den Server von Sprechen und Google (Gemini), und bewertet wird dann nur der Text, der
während des Gesprächs live erkannt wurde; dieser Text geht wie oben beschrieben an den Server und an
Anthropic.

Die Verarbeitung deiner Zugangsdaten, des Ergebnisses, deiner Problemmeldungen und der technischen
Daten ist für die Bereitstellung des von dir angefragten Testzugangs erforderlich
(Art. 6 Abs. 1 lit. b DSGVO); die technischen Daten dienen außerdem unserem berechtigten Interesse an
einem sicheren und funktionierenden Betrieb (Art. 6 Abs. 1 lit. f DSGVO).

Transkripte, Ergebnisse und Rückmeldungen nutzt der Betreiber außerdem, um Sprechen zu verbessern (zum Beispiel
beim Prüfen der Bewertungsregeln an gespeicherten Sitzungen); Tonaufnahmen hört er nur zur Fehlersuche an.
Grundlage für die Verbesserung ist unser berechtigtes Interesse an einem funktionierenden Übungsangebot
(Art. 6 Abs. 1 lit. f DSGVO); du kannst dieser Nutzung jederzeit widersprechen (siehe „Deine Rechte").

## Speicherdauer

- **Ton auf dem Server:** wird **7 Tage nach abgeschlossener Auswertung gelöscht**. Konnte eine
  Auswertung nicht abgeschlossen werden, wird die Aufnahme nicht automatisch gelöscht; der Betreiber
  entfernt sie bei der Bereinigung des Profils, spätestens auf deine Anfrage hin.
- **Bei Google und Anthropic:** Die für die Auswertung hochgeladene Aufnahme löscht der Server von Sprechen
  bei Google direkt nach der Verarbeitung; spätestens löscht Google sie 48 Stunden nach dem Hochladen
  automatisch. Darüber hinaus speichert Google Anfragen und Antworten bis zu 55 Tage, um Missbrauch zu
  erkennen (Einsicht nur durch dazu befugte Google-Mitarbeitende); Anthropic löscht Eingaben und Ausgaben in der Regel innerhalb von 30 Tagen (länger nur bei
  Verdacht auf einen Verstoß gegen seine Nutzungsbedingungen).
- **Ergebnis und Transkripte:** bleiben in deinem Profil, bis du ihre Löschung verlangst. Auf deine
  Anfrage löscht der Betreiber alle Sitzungen, Tonaufnahmen und Ergebnisse deines Zugangs.
- **Problemmeldungen:** löscht der Betreiber nach der Bearbeitung und dem Ende der Korrespondenz aus seinem
  Postfach.
- **Rückmeldungen (Umfrage):** bleiben auf dem Server, bis du ihre Löschung verlangst.
- **Zugangsname:** Bei Testzugängen ist der Benutzername dein Vorname. Er bleibt in der Kontoverwaltung
  des Servers auch nach dem Schließen des Zugangs vermerkt und kann in Sicherungskopien der
  Kontoverwaltung sowie in automatisch rotierenden Server-Protokollen (ohne Gesprächsinhalte) enthalten
  sein; auf Anfrage entfernt der Betreiber auch diese Einträge. Die Daten der Testzugänge sind nicht
  Teil der nächtlichen Datensicherung des Servers.

## Auf deinem Gerät

**Web-App im Browser**

- Benutzername und Passwort speichert dein Browser (Anmeldung über den Browser), nicht die Anwendung;
  du kannst sie in den Einstellungen des Browsers löschen.
- Im Speicher des Browsers liegen eine Kopie des laufenden Gesprächs und Kopien noch nicht übertragener
  Gespräche. Die Kopie eines Gesprächs wird entfernt, sobald das Ergebnis auf dem Server gesichert ist.
- Tonaufnahmen bleiben in der Datenbank des Browsers (ohne Auswertung nur die letzten zwei; eine Aufnahme mit
  Auswertung bleibt, bis du sie löschst); du kannst sie unter „Verlauf" jederzeit löschen. Wählst du nur die
  lokale Sicherheitskopie, werden diese Aufnahmen nicht hochgeladen.
- Benachrichtigungen des Browsers (etwa wenn das Ergebnis fertig ist) gibt es nur, wenn du sie erlaubst.
- Das Löschen der Website-Daten von `sprechen.deutsch.quest` im Browser entfernt alle lokal
  gespeicherten Daten.

**Android-App**

- Die letzten zwei Tonaufnahmen und bis zu 30 Gesprächskopien bleiben auf dem Handy. Die Aufnahmen
  kannst du jederzeit selbst löschen — unter „Verlauf" und direkt nach dem Gespräch auf dem
  Ergebnisbildschirm. Die Kopie eines Gesprächs wird automatisch gelöscht, sobald das Ergebnis auf dem
  Server gesichert ist.
- Dein Profilpasswort wird auf dem Gerät verschlüsselt gespeichert (Android Keystore, AES-GCM) und
  verlässt das Gerät nur zur Anmeldung bei deinem Profil.
- Gespräche, Tonaufnahmen und Zugangsdaten werden **nicht** in die Google-Sicherung deines Handys
  übernommen und **nicht** auf ein neues Gerät übertragen.
- Beim Deinstallieren der App werden alle lokal gespeicherten Daten entfernt.
- Berechtigungen: **Mikrofon** (Aufnahme deiner Antworten während des Gesprächs),
  **Benachrichtigungen** (Hinweis, dass die Prüfung noch läuft, und Nachricht, sobald das Ergebnis
  fertig ist), **Vordergrunddienst** (Mikrofon, Datenabgleich — damit das Gespräch bei ausgeschaltetem
  Bildschirm weiterläuft und die Aufnahme danach vollständig übertragen wird), **Internet und
  Netzwerkstatus** (Verbindung zum Server).

## Sicherheit

- Alle Verbindungen laufen verschlüsselt (HTTPS bzw. WSS).
- Der Server wird bei Exoscale in Sofia (EU) betrieben; auf die gespeicherten Daten greift nur der
  Betreiber zu. Zur Fehlersuche kann er auch Aufnahmen anhören.

## Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und
Datenübertragbarkeit sowie auf Widerruf deiner Einwilligung mit Wirkung für die Zukunft. Gegen eine
Verarbeitung auf Grundlage berechtigter Interessen kannst du aus Gründen deiner besonderen Situation
Widerspruch einlegen. Der Nutzung deiner Transkripte, Ergebnisse und Rückmeldungen zur Verbesserung von
Sprechen kannst du jederzeit ohne Angabe von Gründen widersprechen; wir nutzen sie dann nicht mehr dafür. Für
Auskunft, Löschung oder Widerspruch genügt eine Nachricht an die oben genannte Kontaktadresse.

Außerdem kannst du dich bei einer Datenschutz-Aufsichtsbehörde beschweren, insbesondere bei der
[Landesbeauftragten für Datenschutz und Informationsfreiheit Nordrhein-Westfalen](https://www.ldi.nrw.de/beschwerde).

## Kinder

Die Anwendung richtet sich an Erwachsene und an Jugendliche in der Erwachsenenbildung. Sie ist nicht
für Kinder unter 13 Jahren bestimmt.

## Änderungen

Änderungen dieser Erklärung werden auf dieser Seite mit aktualisiertem Datum veröffentlicht.

---

# Privacy Policy – DTB B2 Sprechen (English)

**Last updated:** 2026-10-07

## Overview

Sprechen (DTB B2 Sprechen) is an application for practising the speaking part of the German exam
"Deutsch-Test für den Beruf B2". It runs a simulated exam conversation with an AI examiner and then
evaluates the performance. It comes in two forms: a **web app** in the browser at
`sprechen.deutsch.quest` and an **Android app**. Both use the same server and process your data in the
same way; differences in what is stored on your device are described in the section "On your device".

Access is granted personally (test access). Sprechen is not an official examination service; the AI
evaluation is for practice.

**Data controller:** Dawid Mazurek
**Contact:** derdavid@deutsch.quest
**Postal address:** see the [Sprechen imprint](https://sprechen.deutsch.quest/zugang/?lang=en&legal=imprint)

Requests sent through the form at [sprechen.deutsch.quest/zugang](https://sprechen.deutsch.quest/zugang/)
are covered by the privacy notice linked there.

## What data is processed

- **Voice recording** of the exam conversation, up to 20 minutes per session. Background noise may be
  captured as well.
- **Conversation text** (transcript) and the exam tasks you were given.
- **Evaluation result.**
- **Problem reports** you send yourself from the application ("Problem mit diesem Gespräch melden"):
  the chosen reason, your optional text and the session number.
- **Feedback on the test version** (survey in the application): your answers, linked to your account and,
  where applicable, to the exam concerned.
- **Optional pronunciation practice** after the exam: a short recording (10 to 90 seconds) that you send to
  Google yourself via our server with "Analysieren"; it is not stored on our server.
- **Technical session data** for troubleshooting: connection quality, interruptions, type and version
  of your browser or device, and the application version.
- **Profile credentials**: profile address, username (for test accounts, your first name) and password.

No advertising, analytics or tracking tools are used, no cookies are set, and no profiling takes place.

## Who processes the data

The application holds **no API keys**. It talks only to the Sprechen server, which applies the keys and
forwards data:

| Recipient | What it receives | Purpose |
|---|---|---|
| Sprechen server (`sprechen.deutsch.quest`), hosted by Exoscale in Sofia, Bulgaria (EU) | Voice recording, transcript, result, technical data, account name | Storage, evaluation, display of the result |
| Google (Gemini) | Live audio of the conversation; afterwards the recording | Conversation with the examiner; new transcript and pronunciation assessment |
| Anthropic (Claude) | **text only** — transcript and exam tasks | Generating tasks, linguistic and content evaluation |

**No audio is sent to Anthropic.** Problem reports from the application travel by e-mail via Resend (sending)
and Porkbun (forwarding) to the operator's Gmail mailbox (Google); they are not additionally stored as a file
on the Sprechen server. Survey answers are stored only on the Sprechen server. Beyond this, no data is shared
with third parties.

During the conversation (Google) and when the tasks are generated (Anthropic) our server forwards your browser's
requests; technical details such as your IP address and browser type may be passed along.

**Transfers to the USA.** Google and Anthropic also process the data in the USA; the same applies to Resend,
Porkbun and Google (Gmail) for problem reports sent by e-mail. The transfers rely on
the EU Commission standard contractual clauses and, where the provider is certified, on the EU-US Data
Privacy Framework. Both providers process the data on our behalf under their API terms; under those
terms the content is not used to train their language models (Gemini, Claude). Details:
[Google privacy policy](https://policies.google.com/privacy),
[Gemini API terms](https://ai.google.dev/gemini-api/terms),
[Anthropic privacy policy](https://www.anthropic.com/privacy).

## Consent and legal bases

Recording and its processing take place only with your explicit **consent** (Art. 6(1)(a) GDPR), which
you give on the "Vorbereitung" (preparation) screen before each conversation. In the web app you choose
there between recording with evaluation and a local-only backup copy. You can decline consent there at
any time and withdraw it at any time with effect for the future. Without this consent no voice recording
is uploaded. The conversation itself still runs through the Sprechen server and Google (Gemini), and
only the text recognised live during the conversation is evaluated; that text goes to the server and
to Anthropic as described above.

Processing of your credentials, the result, your problem reports and the technical data is necessary to
provide the test access you requested (Art. 6(1)(b) GDPR); the technical data also serves our
legitimate interest in secure and reliable operation (Art. 6(1)(f) GDPR).

The operator also uses transcripts, results and feedback to improve Sprechen (for example when checking the
evaluation rules against stored sessions); voice recordings are listened to only for troubleshooting. The
improvement is based on our legitimate interest in a working practice service (Art. 6(1)(f) GDPR); you may
object to this use at any time (see "Your rights").

## Retention

- **Audio on the server:** deleted **7 days after the analysis has been completed**. If an analysis
  could not be completed, the recording is not deleted automatically; the operator removes it when
  cleaning up the profile, and at the latest upon your request.
- **At Google and Anthropic:** the Sprechen server deletes the recording uploaded for evaluation at Google
  right after processing; at the latest, Google deletes it automatically 48 hours after upload. Beyond that,
  Google keeps prompts and responses for up to 55 days to detect abuse (they can be accessed for review only by
  authorised Google staff); Anthropic deletes inputs and outputs
  normally within 30 days (longer only where it suspects a violation of its usage policy).
- **Result and transcripts:** kept in your profile until you request deletion. Upon your request the
  operator deletes all sessions, voice recordings and results of your account.
- **Problem reports:** the operator deletes them from the mailbox after handling the report and ending the
  correspondence.
- **Feedback (survey):** kept on the server until you request deletion.
- **Account name:** for test accounts the username is your first name. It remains recorded in the
  server's account management after the account is closed and may be contained in backup copies of the
  account management and in automatically rotating server logs (without conversation content); upon
  request the operator removes these entries as well. Data of test accounts is not part of the server's
  nightly backup.

## On your device

**Web app in the browser**

- Your username and password are stored by your browser (browser sign-in), not by the application; you
  can delete them in the browser settings.
- The browser storage holds a copy of the current conversation and copies of conversations not yet
  transferred. A conversation copy is removed as soon as the result is stored on the server.
- Voice recordings remain in the browser database (without evaluation only the last two; a recording with
  evaluation stays until you delete it); you can delete them at any time under "Verlauf". If you choose the
  local-only backup copy, these recordings are not uploaded.
- Browser notifications (for example when the result is ready) appear only if you allow them.
- Clearing the site data of `sprechen.deutsch.quest` in your browser removes all locally stored data.

**Android app**

- The last two voice recordings and up to 30 conversation copies remain on your phone. You can delete
  the recordings yourself at any time — under "Verlauf" (history) and on the result screen right after
  a conversation. A conversation copy is deleted automatically as soon as the result is stored on the
  server.
- Your profile password is stored encrypted on the device (Android Keystore, AES-GCM) and leaves it only
  to sign in to your profile.
- Conversations, recordings and credentials are **excluded** from Google backup and from
  device-to-device transfer.
- Uninstalling the app removes all locally stored data.
- Permissions: **microphone** (recording your answers during the conversation), **notifications**
  (showing that the exam is still running and telling you when the result is ready), **foreground
  service** (microphone, data sync — so the conversation continues while the screen is off and the
  recording finishes uploading afterwards), **internet and network state** (connection to the server).

## Security

- All connections are encrypted (HTTPS / WSS).
- The server is hosted by Exoscale in Sofia (EU); only the operator has access to the stored data. For
  troubleshooting the operator may also listen to recordings.

## Your rights

You have the right of access, rectification, erasure, restriction of processing and data portability,
and the right to withdraw your consent with effect for the future. You may object, on grounds relating
to your particular situation, to processing based on legitimate interests. You may object at any time, without
giving reasons, to the use of your transcripts, results and feedback for improving Sprechen; we will then stop
using them for that purpose. A message to the contact address above is enough for access, erasure or objection.

You may also lodge a complaint with a data protection supervisory authority, in particular the
[State Commissioner for Data Protection and Freedom of Information of North Rhine-Westphalia](https://www.ldi.nrw.de/beschwerde).

## Children

The application is intended for adults and for young people in adult education. It is not directed at
children under 13.

## Changes

Changes to this policy will be published on this page with an updated date.


