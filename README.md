# Packet Defender: An Educational Web-Based Network Game (v2.5)

**A single-file HTML/JavaScript game designed by Wes Fryer and collaboratively "vibecoded" with Gemini, the AI assistant.**

Packet Defender is a fast-paced, educational, single-player game created to help middle school students understand fundamental networking and cybersecurity concepts through interactive gameplay.

## 🎓 Educational Goals

The core objective is to gamify essential Internet terminology and processes:

* **IP Addressing:** Students must correctly identify and enter IP addresses for successful transmission.
* **DNS Resolution:** Every packet displays a **Domain Name**, requiring the student to look up the corresponding **IP Address** using the on-screen DNS Lookup Table.
* **Packet Transmission (Routing):** Players match packet details (Origin IP, Name, Destination IP) to successfully route the data.
* **Cybersecurity Defense:** Students must identify "under attack" packets (colored red) and use the **Defend Server** action to earn higher points, simulating a firewall or mitigation response.

## 🕹️ Game Features

* **Single-File Deployment:** The entire game runs from a single HTML file (HTML, CSS, and JavaScript contained within), making deployment instant.
* **Difficulty Modes:** Students can select Easy (60s refresh), Intermediate (45s refresh), or Hard (30s refresh) timers.
* **Overall Game Timer:** A 5-minute timer encourages competitive play and score tracking against classmates.
* **Persistent Score:** The player's score is saved in their browser's local storage and persists across page reloads until they choose to restart the game.
* **Visual Feedback:** Includes colorful packet queuing, a visible countdown, and a simple ASCII animation upon successful action.

## 🚀 How to Deploy on GitHub Pages

Since the entire game is in a single file, deployment is simple and can be done in two phases.

### Phase 1: Uploading the New Code

1.  **Rename/Save File:** Ensure your final, working code is saved as a single file, typically named **`index.html`** or **`packet-defender.html`**.
2.  **Open Your Repository:** Go to your existing `packet-defender` repository on GitHub: `https://github.com/wfryer/packet-defender`.
3.  **Navigate to the Code View:** Click on the **`Code`** tab.
4.  **Edit the Existing File:** Click on the name of your old HTML file (e.g., `index.html`) to view its contents.
5.  **Replace Content:** Click the **pencil icon** (`Edit this file`) and **replace all** the existing code with the complete, new code you just finalized.
6.  **Commit Changes:** Scroll to the bottom, enter a clear commit message (e.g., "Feature complete v2.5: Added name display, 5m timer, and forced DNS lookup."), and click **Commit changes**.

### Phase 2: Confirming GitHub Pages Deployment

Your GitHub Pages link (`https://wfryer.github.io/packet-defender/`) should update automatically within 1–5 minutes. If it doesn't, follow these steps to confirm the settings:

1.  **Go to Settings:** In your `packet-defender` repository, click the **`Settings`** tab.
2.  **Navigate to Pages:** In the left sidebar, click on **`Pages`**.
3.  **Check Source:** Ensure that under "Build and deployment," the settings are:
    * **Source:** **Deploy from a branch**
    * **Branch:** **`main`** (or whichever branch holds your HTML file)
    * **Folder:** **`/ (root)`**
4.  **Save/Wait:** If you made any changes, click **Save**. You should see a message at the top of the Pages screen confirming your site is now being built.
5.  **Test:** Your new, feature-complete version will be live at:
    `https://wfryer.github.io/packet-defender/`

Good luck with your students! I hope they enjoy the game and the improved features.
