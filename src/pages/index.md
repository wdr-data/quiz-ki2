---
title: "Deepfake-Quiz: Erkennen Sie alle KI-Videos und -Audios?"
description: Mit diesem Quiz können Sie überprüfen, ob und wie gut Sie mit KI erzeugte Audios und Videos erkennen.
author: Jörg Schieb
pub_date: "2023-06-02"
heroImage: "header.jpg"
heroAlt: "Ein Roboter, generiert mit KI"
heroCredit: ""
sharingImageFacebook: "header.jpg"
sharingImageTwitter: "header.jpg"
cg1: "WDR"
cg2: "Data"
cg3: "Newsroom"
cg4: "Deepfake Quiz 2"

pageType: "Quiz"
editorialDepartment: "Newsroom"
---

import Sharing from '../components/sharing/sharing.jsx'
import WdrPlayer from '../components/video/video.jsx'
import { Link, LinkList } from '../components/link/link.jsx'
import { Quiz, Image as QuizImage, Video as QuizVideo, Audio as QuizAudio, Question, Answer, Result, Score as QuizScore } from '../components/quiz/quiz.jsx'

# Deepfake-Quiz: Erkennen Sie alle KI-Videos und <nobr>-Audios</nobr>?

## Mit diesem Quiz können Sie überprüfen, ob und wie gut Sie mit KI erzeugte Audios und Videos erkennen.

Es hat sich mittlerweile herumgesprochen: Künstliche Intelligenz (KI) ist nicht nur sehr gut daran, große Datenmengen zu analysieren oder Gesichter zu erkennen, sondern kann auch selbst Inhalte generieren. Der bekannte Chatbot ChatGPT zum Beispiel erstellt mühelos gut lesbare Texte. Bildgenerierende KI-Systeme wie Midjourney oder Stable Diffusion erzeugen verblüffend realistisch aussehende Fotos (siehe unser Quiz dazu).

Die nächste Stufe sind Audios und Videos: Auch die lassen sich heute mit Hilfe von KI mit verhältnismäßig geringem Aufwand komplett künstlich erzeugen.

### Auch Fake von Stimmen und Videos möglich

Was vor einigen Monaten noch nur im Labor möglich war, steht heute jedem offen: KI-Systeme, die mit synthetischer Stimme sprechen, die völlig echt klingen. Aber auch KI-Systeme, die praktisch jede Stimme nahezu perfekt nachahmen können. Es reichen einige wenige Minuten Audiomaterial – etwa eine Rede! –, schon lässt sich mit KI ein Audioschnipsel bauen, in dem alles gesagt werden kann. Ein Audio Deepfake.

Mit Videos ist es etwas aufwändiger und die Ergebnisse können noch nicht ganz so überzeugen – aber auch hier werden enorme Fortschritte gemacht.

Wir haben in diesem Quiz Aufnahmen im Angebot: Audios und Videos. Echte und unechte. Die Aufgabe ist es zu entscheiden: Sie die Aufnahmen nun echt oder unecht? Auf diese Weise lässt sich gut erkennen und lernen, was heute schon möglich ist – und worauf man achten muss, um Deepfakes zu enttarnen.

Viel Spaß beim Quiz!

#### Olaf Scholz Rede

Diese Audioaufnahme des Kanzlers: Eine echte Rede, gehalten vor dem Parlament – oder eher ein Fake? Entscheiden Sie selbst, nachdem Sie sich das Audio in aller Ruhe angehört haben...

<Quiz>
<QuizAudio src="Scholz3.mp3" />
<Question>**Ist die Aufnahme echt oder fake?**</Question>
<Answer correct>Echt</Answer>
<Answer>Fake</Answer>
<Result>
Die Rede hat Olaf Scholz am 7.9.2022 vor dem Deutschen Bundestag gehalten.\n
Quelle: [Deutscher Bundestag](https://dserver.bundestag.de/btp/20/20050.pdf)
</Result>
</Quiz>

#### Olaf Scholz liest den Kleinen Prinzen

Olaf Scholz hat im Wahlkampf auch Schulen besucht – und teilweise vorgelesen. In dieser Aufnahme liest der Kanzler eine Passage aus dem „Kleinen Prinzen“ von Antoine de Saint-Exupéry. Eine echte Aufnahme – oder etwa ein Deepfake?

<Quiz>
<QuizAudio src="Scholz_kleiner_prinz.mp3" />
<Question>**Ist die Aufnahme echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Diese Aufnahme wurde mit Hilfe eines KI-Werkzeugs erzeugt, in diesem Fall Elevenlabs. Es reichen einige Minuten Audiomaterial in guter Qualität – von Politikern und Menschen in der Öffentlichkeit immer leicht zu besorgen –, schon lässt sich die Stimme „klonen“. Kleine Feinheiten könnten noch nachjustiert werden. In Englischer Sprache klingen die Ergebnisse bereits viel besser und sind von der Realität praktisch nicht mehr zu unterscheiden.
</Result>
</Quiz>


#### Stauschau, mal anders

Die Stauschau: Im Radio ein Klassiker. Hat Olaf Scholz diese Stauschau bei seinem Besuch im WDR2-Studio zuletzt aus Spaß selbst gesprochen, um die Hörer zu unterhalten?

<Quiz>
<QuizAudio src="Scholz_Stauschau.mp3" />
<Question>**Ist die Aufnahme echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Auch diese Aufnahme ist ein Fake. Sie zeigt aber: Es ist durchaus möglich, die Stimme von so ziemlich jedem nachzuahmen – und mit Hilfe von KI alles sagen zu lassen. Durch die Fortschritte bei der Entwicklung der KI-Systeme wird die Audioqualität immer besser. Schon bald ist kein Unterschied mehr zu echten Stimmen zu hören.
</Result>
</Quiz>

#### Donald Trump liebt Pizza

Einige Menschen haben unverwechselbare Stimmen – Donald Trump gehört ohne jede Frage dazu. So wie er spricht, so spricht kein anderer. Hier nun ein Tondokument in amerikanischer Sprache. Er sagt:

„Hey people of Germany. You know I love you. And I know, you love me, too. So much you love me. And I love your pizza... So, that is why I decided to run for president in Germany. Cool or cool?“

Aber hat er das wirklich gesagt?

<Quiz>
<QuizAudio src="Trump_Germany2.wav" />
<Question>**Ist die Aufnahme echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Nein, hat er natürlich nicht. Es gibt Dutzende von Apps, die prominente Stimmen nachahmen – teilweise sogar in Echtzeit. Das bedeutet: Man kann ins Mikrofon sprechen – und die eigene Stimme wird augenblicklich so verstellt, dass sie wie der oder die Prominente klingt.  Andere Onlinedienste wie FakeYou.com erlauben, eine Stimme auszuwählen – und danach wird mit der Stimme alles gesagt, was man möchte. Wie in diesem Fall. Wer nicht genau hinhört, kann leicht darauf hereinfallen.
</Result>
</Quiz>

#### Tagesschau: Täglich frisch von Ihrem Avatar...

Die Tagesschau informiert täglich Millionen Menschen verlässlich mit aktuellen Nachrichten, Berichten und Reportagen aus aller Welt. Das wird auch in Zukunft tun. Doch was, wenn KI zum Einsatz kommt – oder käme?

<Quiz>
<QuizVideo src="TS-100-Sekunden.mp4" />
<Question>**Ist das Video echt oder fake?**</Question>
<Answer correct>Echt</Answer>
<Answer>Fake</Answer>
<Result>
Diese Ausgabe der „Tagesschau in 100 Sekunden“ ist ein Original, moderiert von Carl-Georg Salzwedel. Sie wird vor allem für Social Media und online produziert – und hier auch ausgespielt. Vielleicht könnten Sie denken, die Ausgabe sei Fake, weil Sie den Moderator nicht (gut) kennen. Doch hier ist alles „handgemacht“: Echte Menschen vor der Kamera, echte Stimme, echte Beiträge.
</Result>
</Quiz>

Aber was, wenn man den Präsentator künstlich erzeugen würde? Das könnte dann zum Beispiel so aussehen...

<Quiz>
<QuizVideo src="Tagesschau_Avatar.mp4" />
<Question>**Ist das Video echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Hier ist der Präsentator unübersehbar ein Avatar, der künstlich erzeugt wurde. Mit einem Text, der von einem Menschen gesprochen wurde. Der Avatar bewegt sich – trotz seiner comichaften Erscheinung – einigermaßen natürlich und vor allem spricht er lippensynchron. So etwas ist heute kein Problem mehr. Hier hat die KI-Software „Synthesia“ ausgeholfen: Stimme echt, Avatar künstlich – und der Background mit den Infotafeln ebenfalls.
</Result>
</Quiz>


Die echte Tagesschau setzt noch keine Avatare ein. Aber nicht alle Präsentatoren und Moderatoren sind schon bekannt. So wie Sebastian Keyzer, der wegen seiner sonoren Stimme auch häufig zum Sprechen von Filmtexten gebucht wird.

<Quiz>
<QuizVideo src="TS-Fake.mp4" />
<Question>**Ist das Video echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Auch das ist ein Fake. Wir haben den originalen Ton aus der „Tagesschau in 100 Sekunden“ genommen. Der Ton ist also echt. Doch der Avatar, eine aus einer großen Zahl von Präsentatoren in Synthesia, ist komplett virtuell – und bewegt sich und spricht so, wie der Text es vorgibt.
</Result>
</Quiz>


Für alle, die sich beklagen wollen, dass wir bislang nur Männer präsentiert haben: Hier nun einmal „Tagesschau“ mit Evelyn Hörster aus Dortmund. Man hört die Herkunft noch ein bisschen raus. Wie gefällt Ihnen diese Präsentatorin der Tagesschau?

<Quiz>
<QuizVideo src="TS female.mp4" />
<Question>**Ist das Video echt oder fake?**</Question>
<Answer>Echt</Answer>
<Answer correct>Fake</Answer>
<Result>
Auch das: Fake. Sowohl die Stimme ist künstlich mit KI erzeugt, als auch der weibliche Avatar. Das alles hat Synthesia erstellt. Der Hintergrund mit den Berichten wurde in der Schnitt-Software zusammengesetzt.
</Result>
</Quiz>

Das herzustellen, hat nicht mal 15 Minuten gedauert. Es ist also wirklich wichtig, auf Details zu achten. Noch sind die Avatare etwas unscharf. Doch einige KI-Modelle können die Präsentatoren bereits in 4K und gestochen scharf erzeugen. Dasselbe gilt für die Sprache: In Englisch ist der Output der KI kaum noch zu erkennen. Die Fortschritte, die hier gemacht werden, sind enorm.

Solche Situationen sind die Klassiker für Fake-Videos: Man nehme einen Politiker – in diesem Fall eine Politikerin – und lege einen beliebigen Ton darunter. Versprecher. Falsche Aussagen. Blamagen. So etwas geht dann viral... Wie auch dieser Ausschnitt einer Debatte, die auf Youtube häufig geteilt wurde. Echt oder Fake?

<Quiz>
<QuizVideo src="Baerbock.mp4" poster="baerbock_thumb.jpg" />
<Question>**Ist das Video echt oder fake?**</Question>
<Answer correct>Echt</Answer>
<Answer>Fake</Answer>
<Result>
Dieses Video ist echt. Es handelt sich um einen echten Versprecher im Bundestag: Bild und Ton sind nicht manipuliert. Aber selbst wenn, wäre es schwierig nachzuweisen, da die Lippenbewegungen nicht gut zu erkennen sind.
</Result>
</Quiz>

<QuizScore
images={{
    0: "result_bad.png",
    5: "result_ok.png",
    8: "result_good.png",
}}
texts={{
    0: "Es ist wirklich schwierig. Aber Sie haben sich noch von zu vielen Deepfakes täuschen lassen. Einfach ein bisschen üben, kritischer rangehen – und auf das Bauchgefühl hören!",
    5: "Das war schon sehr gut: Die meisten Fakes erkannt – aber auf einige dann doch noch hereingefallen. Einfach noch mehr üben, kritischer rangehen – und auf das Bauchgefühl hören!",
    8: "Das ist ein sehr gutes Ergebnis: Die meisten oder alle Deepfakes erkannt. Gratuliere, Sie lassen sich nicht so leicht an der Nase herumführen. Aber jetzt bitte nicht auf den Lorbeeren ausruhen.",
}}
/>

#### Mehr zum Thema beim WDR

<LinkList links={[
    { href: "https://www1.wdr.de/nachrichten/deepfakes-100.html", title: "Deepfakes: Wir können unseren Augen und Ohren nicht mehr trauen" },
    { href: "https://data.wdr.de/ddj/deepfake-quiz-erkennen-sie-alle-ki-bilder/", title: "Deepfake-Quiz: Erkennen Sie alle KI-Bilder?" },
	{ href: "https://data.wdr.de/ddj/ki-jobs-arbeit-zukunft/", title: "So stark ist Ihr Job durch KI bedroht" },
    { href: "https://reportage.wdr.de/kollege-roboter-die-loesung-fuer-den-fachkraeftemangel", title: "Kollege Roboter: Die Lösung für den Fachkräftemangel?" },
]} />

Hinweis der Redaktion: In einer früheren Version stand, dass Olaf Scholz die Rede am 9.5.2023 vor dem EU-Parlament in Straßburg gehalten hatte. Das ist so nicht richtig, wir bitten den Fehler zu entschuldigen.

<Sharing twitter facebook mail whatsapp telegram reddit xing linkedin />
