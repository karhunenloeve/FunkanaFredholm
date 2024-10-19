# Fredholm-Operatoren
# Fredholm-Operatoren

Ein Fredholm-Operator $T$ ist ein Operator zwischen Banachräumen, für den die Lösungen des inhomogenen linearen Problems $T x = y$ durch „endlich viele Daten“ charakterisiert werden können, ähnlich wie im endlich-dimensionalen Fall. Konkret bedeutet dies, dass der Kern $\ker(T)$ endlich-dimensional ist, d.h. es existiert eine endliche Basis $\{v_1, \dots, v_n\}$ für $\ker(T)$. Ebenso ist der Kokern $\text{coker}(T) = Y / \text{Im}(T)$ endlich-dimensional, sodass es endlich viele lineare Funktionale $\{\varphi_1, \dots, \varphi_k\}$ auf $Y$ gibt, welche der Bedingung $y \in \text{Im}(T)$ genügen. Diese Bedingung ist äquivalent zu $\varphi_1(y) = \dots = \varphi_k(y) = 0$. 

Die Gleichung $T x = y$ besitzt genau dann eine Lösung, wenn $\varphi_1(y) = \dots = \varphi_k(y) = 0$. Falls eine Lösung existiert, bildet die Lösungsmenge eine endliche affine Untermenge, gegeben durch $x_0 + \langle v_1, \dots, v_n \rangle$, wobei $x_0$ eine spezielle Lösung des inhomogenen Problems ist, d.h. $T x_0 = y$.

Der Index von $T$ ist definiert als die Differenz der Dimension des Kerns mit der des Kokerns: $\text{ind}(T) = \dim(\ker(T)) - \dim(\text{coker}(T))$.

Ein entscheidender Aspekt des Index ist seine Invarianz gegenüber kompakten Störungen und seine Stetigkeit auf der offenen Menge der Fredholm-Operatoren. Die Zusammenhangskomponenten dieser Menge stehen in Bijektion mit dem Index.

Im endlich-dimensionalen Fall, wenn $T: \mathbb{C}^n \to \mathbb{C}^n$ eine lineare Abbildung ist, ist $T$ automatisch ein Fredholm-Operator mit Index Null. Sei $\lambda \in \mathbb{C}$, dann ist der Kern von $T - \lambda I$ für fast alle $\lambda$ trivial und $T - \lambda I$ surjektiv, außer wenn $\lambda$ ein Eigenwert von $T$ ist. In diesem Fall erhöht sich die Dimension des Kerns (um die geometrische Vielfachheit von $\lambda$), während die Dimension des Bildes gemäß dem Rang-Nullitätssatz um denselben Betrag abnimmt, sodass der Index erhalten bleibt.

Im unendlich-dimensionalen Fall gilt der Rang-Nullitätssatz im Allgemeinen nicht, und es besteht im Normalfall kein einfacher Zusammenhang zwischen den Dimensionen von $\ker(T)$ und $\text{Im}(T)$. Für Fredholm-Operatoren $T: X \to Y$ mit Index $L$ jedoch beschreibt $L$ die Differenz zwischen den Dimensionen des Kerns und des Kokerns.

Wenn $X = Y$ ist und $T - \lambda I$ für alle $\lambda$ Fredholm bleibt, dann wird der Sprung in der Dimension des Kerns von $T - \lambda I$, wenn $\lambda$ ein Eigenwert ist, sowie die entsprechende Abnahme der Dimension des Bildes, durch den Index $L$ bestimmt. Für $L = 0$ gleichen sich diese Sprünge aus. Ist $L > 0$, so kann $T - \lambda I$ nicht injektiv sein; falls $T - \lambda I$ surjektiv ist, beträgt die Dimension des Kerns genau $L$. Generell kann die Dimension des Kerns von $L$ auf $L + r$ (mit $r > 0$) anwachsen, wobei die Dimension des Bildes um $r$ abnimmt, um dies zu kompensieren. Dies bedeutet, dass die Dimension des Kokerns ebenfalls um $r$ zunimmt. Wenn $L < 0$ ist, kann $T - \lambda I$ nicht surjektiv sein, und eine analoge Analyse ergibt sich.

## 📚 Inhalte

In diesem Repository findest du:
- **Grundlagen der Fredholm-Operatoren**: Eine präzise Definition und wichtige Eigenschaften, die Fredholm-Operatoren in der Funktionalanalysis auszeichnen.
- **Beispiele und Anwendungen**: Anwendungsfälle, in denen Fredholm-Operatoren auftreten, z.B. in der Theorie elliptischer Differentialoperatoren.
- **Mathematische Beweise**: Ausführliche Beweise zur Stabilität von Fredholm-Operatoren unter kompakten Störungen und deren Rolle in der Funktionalanalysis.
- **LaTeX-Dateien**: Alle Inhalte sind in LaTeX vorbereitet und eignen sich perfekt für wissenschaftliche Arbeiten.

## 📄 Download der Dokumentation

Die gesamte Theorie und die dazugehörigen Beweise kannst du bequem als PDF-Dokument herunterladen. Klicke einfach auf den folgenden Link:

[📥 Download Fredholm-Dokumentation (PDF)](https://github.com/karhunenloeve/FunkanaFredholm/raw/main/Fredholm_Operatoren.pdf)

> **Hinweis:** Wenn du die LaTeX-Dateien selbst kompilieren möchtest, stelle sicher, dass du eine aktuelle LaTeX-Distribution installiert hast, um alle Pakete und Bibliotheken korrekt zu nutzen.

## 🚀 Installation und Nutzung

Falls du das Projekt auf deinem lokalen Rechner klonen möchtest, führe folgende Schritte aus:

1. Öffne dein Terminal.
2. Klone das Repository mit:

    ```bash
    git clone https://github.com/karhunenloeve/FunkanaFredholm.git
    ```

3. Navigiere ins Verzeichnis:

    ```bash
    cd FunkanaFredholm
    ```

4. Kompiliere die LaTeX-Dateien (wenn du selbst Änderungen vornehmen möchtest):

    ```bash
    pdflatex main.tex
    ```

5. Genieße die mathematische Schönheit von Fredholm-Operatoren!

## 🧠 Voraussetzungen

- Kenntnisse in Funktionalanalysis und linearen Operatoren sind hilfreich.
- LaTeX-Kenntnisse, falls du die Dokumentation anpassen oder erweitern möchtest.

## 💡 Motivation

Fredholm-Operatoren sind nicht nur von theoretischem Interesse, sondern finden auch breite Anwendung in der Analysis von partiellen Differentialgleichungen, der Spektraltheorie und der numerischen Mathematik. Dieses Projekt zielt darauf ab, die Theorie so zugänglich wie möglich zu machen und bietet eine solide Grundlage für weiterführende Studien.

---

## ✍️ Autoren

Dieses Projekt wurde von denjenigen erstellt, die eine tiefe Liebe zur Funktionalanalysis und Fredholm-Operatoren teilen.

- **karhunenloeve** - [GitHub-Profil](https://github.com/karhunenloeve)

## 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert – siehe die [LICENSE](LICENSE) Datei für weitere Details.