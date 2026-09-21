# Datenschutzerklärung – DTB B2 Sprechen

**Stand:** 2026-09-19

## Überblick

DTB B2 Sprechen ist eine Android-App zum Üben der mündlichen B2-Prüfung Deutsch. Die App führt
ein simuliertes Prüfungsgespräch mit einer KI-Prüferin und bewertet die Leistung anschließend.
Sie wird als geschlossener Test für Teilnehmerinnen und Teilnehmer eines Deutschkurses
bereitgestellt.

**Verantwortlich im Sinne der DSGVO:** `Dawid Mazurek`
**Kontakt:** `dmazurek00@gmail.com`

## Welche Daten verarbeitet werden

- **Tonaufnahme deiner Stimme** während des Prüfungsgesprächs, bis zu 20 Minuten pro Gespräch.
  Umgebungsgeräusche können mit aufgenommen werden.
- **Text des Gesprächs** (Transkript) und die dir gestellten Prüfungsaufgaben.
- **Bewertungsergebnis** deiner Prüfung.
- **Technische Protokolldaten der Sitzung** zur Fehlersuche: Verbindungsqualität, Unterbrechungen,
  Gerätemodell, Android- und App-Version.
- **Zugangsdaten zu deinem Kursprofil**: Adresse des Profils, Benutzername und Passwort.

Es werden **keine** Werbe-, Analyse- oder Tracking-Werkzeuge eingesetzt, es werden keine Cookies
verwendet und es findet keine Profilbildung statt.

## Wer die Daten verarbeitet

Die App kennt **keine API-Schlüssel**. Sie spricht ausschließlich mit dem Kursserver; dieser setzt
die Schlüssel ein und leitet weiter:

| Empfänger | Was er erhält | Wozu |
|---|---|---|
| Kursserver (`roxy.deutsch.quest`) | Tonaufnahme, Transkript, Ergebnis, Protokolldaten | Speicherung, Auswertung, Anzeige des Ergebnisses |
| Google (Gemini) | Ton des laufenden Gesprächs; danach die Tonaufnahme | Gespräch mit der Prüferin; neues Transkript und Bewertung der Aussprache |
| Anthropic (Claude) | **ausschließlich Text** — Transkript und Prüfungsaufgaben | Erstellen der Aufgaben, sprachliche und inhaltliche Bewertung |

**An Anthropic gelangt kein Ton.** Eine Weitergabe an weitere Dritte findet nicht statt.

## Einwilligung und Rechtsgrundlage

Die Aufnahme und ihre Verarbeitung erfolgen nur mit deiner ausdrücklichen Einwilligung
(Art. 6 Abs. 1 lit. a DSGVO), die du vor jedem Gespräch auf dem Startbildschirm erteilst.

Du kannst die Einwilligung dort jederzeit abwählen und sie jederzeit für die Zukunft widerrufen.
Ohne diese Einwilligung wird keine Tonaufnahme hochgeladen. Das Gespräch selbst läuft weiterhin
über den Kursserver und Google (Gemini), und bewertet wird dann nur der Text, der während des
Gesprächs live erkannt wurde; dieser Text geht wie oben beschrieben an den Kursserver und an
Anthropic.

Die Verarbeitung deiner Zugangsdaten stützt sich auf die Durchführung des Kursverhältnisses
(Art. 6 Abs. 1 lit. b DSGVO).

## Speicherdauer

- **Ton auf dem Server:** wird **7 Tage nach abgeschlossener Auswertung gelöscht**. Konnte eine
  Auswertung nicht abgeschlossen werden, wird die Aufnahme nicht automatisch gelöscht; der
  Kursleiter entfernt sie bei der Bereinigung des Kursprofils, spätestens auf deine Anfrage hin.
- **Ergebnis und Transkripte:** bleiben in deinem Kursprofil, bis du ihre Löschung verlangst.
- **Auf deinem Handy:** die letzten zwei Tonaufnahmen und bis zu 30 Gesprächskopien. Die Aufnahmen
  kannst du jederzeit selbst löschen — auf dem Startbildschirm und direkt nach dem Gespräch auf
  dem Ergebnisbildschirm. Die Kopie eines Gesprächs wird automatisch gelöscht, sobald das Ergebnis
  auf dem Server gesichert ist.
- Beim Deinstallieren der App werden alle lokal gespeicherten Daten entfernt.

## Sicherheit

- Alle Verbindungen laufen verschlüsselt (HTTPS bzw. WSS).
- Dein Profilpasswort wird auf dem Gerät verschlüsselt gespeichert (Android Keystore, AES-GCM) und
  verlässt das Gerät nur zur Anmeldung bei deinem Profil.
- Gespräche, Tonaufnahmen und Zugangsdaten werden **nicht** in die Google-Sicherung deines Handys
  übernommen und **nicht** auf ein neues Gerät übertragen.

## Berechtigungen der App

- **Mikrofon** — Aufnahme deiner Antworten während des Gesprächs.
- **Benachrichtigungen** — Hinweis, dass die Prüfung noch läuft.
- **Vordergrunddienst (Mikrofon, Datenabgleich)** — damit das Gespräch bei ausgeschaltetem
  Bildschirm weiterläuft und die Aufnahme danach vollständig übertragen wird.
- **Internet und Netzwerkstatus** — Verbindung zum Kursserver.

## Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung,
Datenübertragbarkeit sowie auf Widerruf deiner Einwilligung mit Wirkung für die Zukunft. Außerdem
kannst du dich bei einer Datenschutz-Aufsichtsbehörde beschweren. Für Auskunft oder Löschung
genügt eine Nachricht an die oben genannte Kontaktadresse.

## Kinder

Die App richtet sich an Erwachsene und an Jugendliche in der Erwachsenenbildung. Sie ist nicht für
Kinder unter 13 Jahren bestimmt.

## Änderungen

Änderungen dieser Erklärung werden auf dieser Seite mit aktualisiertem Datum veröffentlicht.

---

# Privacy Policy – DTB B2 Sprechen (English)

**Last updated:** 2026-09-19

## Overview

DTB B2 Sprechen is an Android app for practising the German B2 speaking exam. It runs a simulated
exam conversation with an AI examiner and then evaluates the performance. It is distributed as a
closed test to participants of a German course.

**Data controller:** `Dawid Mazurek (Hüller Str. 26, 44866 Bochum, Germany)`
**Contact:** `dmazurek00@gmail.com`

## What data is processed

- **Voice recording** of the exam conversation, up to 20 minutes per session. Background noise may
  be captured as well.
- **Conversation text** (transcript) and the exam tasks you were given.
- **Evaluation result.**
- **Technical session logs** for troubleshooting: connection quality, interruptions, device model,
  Android and app version.
- **Course profile credentials**: profile address, username and password.

No advertising, analytics or tracking tools are used, no cookies are set, and no profiling takes
place.

## Who processes the data

The app holds **no API keys**. It talks only to the course server, which applies the keys and
forwards data:

| Recipient | What it receives | Purpose |
|---|---|---|
| Course server (`roxy.deutsch.quest`) | Voice recording, transcript, result, session logs | Storage, evaluation, display of the result |
| Google (Gemini) | Live audio of the conversation; afterwards the recording | Conversation with the examiner; new transcript and pronunciation assessment |
| Anthropic (Claude) | **text only** — transcript and exam tasks | Generating tasks, linguistic and content evaluation |

**No audio is sent to Anthropic.** No data is shared with any other third party.

## Consent and legal basis

Recording and its processing take place only with your explicit consent (Art. 6(1)(a) GDPR), which
you give on the start screen before each conversation. You can decline it there at any time and
withdraw it at any time with effect for the future. Without this consent no voice recording is
uploaded. The conversation itself still runs through the course server and Google (Gemini), and
only the text recognised live during the conversation is evaluated; that text goes to the course
server and to Anthropic as described above.

Processing of your credentials is based on the performance of the course relationship
(Art. 6(1)(b) GDPR).

## Retention

- **Audio on the server:** deleted **7 days after the analysis has been completed**. If an analysis
  could not be completed, the recording is not deleted automatically; the course instructor removes
  it when cleaning up the course profile, and at the latest upon your request.
- **Result and transcripts:** kept in your course profile until you request deletion.
- **On your phone:** the last two voice recordings and up to 30 conversation copies. You can delete
  the recordings yourself at any time — on the start screen and on the result screen right after a
  conversation. A conversation copy is deleted automatically as soon as the result is stored on the
  server.
- Uninstalling the app removes all locally stored data.

## Security

- All connections are encrypted (HTTPS / WSS).
- Your profile password is stored encrypted on the device (Android Keystore, AES-GCM) and leaves it
  only to sign in to your profile.
- Conversations, recordings and credentials are **excluded** from Google backup and from
  device-to-device transfer.

## Permissions

- **Microphone** — recording your answers during the conversation.
- **Notifications** — showing that the exam is still running.
- **Foreground service (microphone, data sync)** — so the conversation continues while the screen is
  off and the recording finishes uploading afterwards.
- **Internet and network state** — connection to the course server.

## Your rights

You have the right of access, rectification, erasure, restriction of processing, data portability,
and withdrawal of consent with effect for the future, as well as the right to lodge a complaint
with a supervisory authority. A message to the contact address above is enough.

## Children

The app is intended for adults and for young people in adult education. It is not directed at
children under 13.

## Changes

Changes to this policy will be published on this page with an updated date.
