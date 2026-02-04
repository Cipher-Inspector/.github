<img width="2759" height="470" alt="CipherInspectorNavLogo (1)" src="https://github.com/user-attachments/assets/83c8176a-732e-44c8-8009-c0e3e7217244" />

# Welcome to Cipher Inspector!

[Cipher Inspector](https://app.cipherinspector.com) is a premium tool for cryptanalysis. Compare and analyze ciphers using a wide variety of established
cryptanalysis techniques, all in a single dashboard. You can even share your analysis with others!

> [!TIP]
> Found an issue? Want to see something added? [Create an issue](https://github.com/Cipher-Inspector/.github/issues/new).

## Basic Features

### Dashboards

<img width="1681" height="768" alt="image" src="https://github.com/user-attachments/assets/326a3edc-4043-445e-a6fd-7647b73200c1" />


CipherInspector Enigma allows you to create insightful dashboards that visualize information about ciphers.

#### Create and save dashboards

Create an account and save all your dashboards to revisit them later. This is a convenient way to ensure your analysis is never lost.

#### Private dashboards

Create dashboards that only you can view, no one else. Have some top secret work you're doing? No worries at all.

#### Public dashboards

If you want to share your dashboard with the world, you can make it public! Anyone with the link will be able to view your dashbard. Public dashboards are read-only and can be made private again.

#### Bookmark Ciphertexts

You can bookmark your favorite ciphertexts and access them from any of the dashboards saved to your account.

### Ciphertexts

<img align="left" width="310" height="583" alt="image" src="https://github.com/user-attachments/assets/17adfd2b-101a-427d-9544-0a2244b57f1c" />


Ciphertexts are input data for the dashboards. Ciphertext inputs accept the text itself, alongside its encoding. Encoding options include "display" encodings such as Latin1, UTF-8, UTF-16,
and UTF-32, as well as "data" encodings such as Binary, Octal, Decimal, Hexadecimal, and Base64. The ciphertext is stored as a bitstream and, depending on the analysis being done, is either
encoded back to its original encoding prior to analysis, or its bytes will be evaluated directly. Ciphertexts are powerful and highly customizable, including:
- Nickname: providing a nickname will help you easily identify your ciphertext in the dashboard
- Color: associating a color with your ciphertext will also help you easily identify your ciphertext in the dashboard
- Transformations: These options act as a way to normalize your analysis and include:
    - Ignore whitespace: Useful if your text is space-separated and spaces are creating noise in the results
    - Ignore punctuation: Useful for ciphertexts with preserved sentence structure
    - Ignore casing: Useful for ciphertexts that contain mixed casing, but it is not required for decryption
    - Genericize: Useful when comparing ciphertexts to observe abstract character patterns
 
<br/><br/>

### Widgets

Widgets are drag-and-drop tools within a dashboard. They can be used to perform analysis or help organize content within the dashboard.
You can find a list of all the widgets and how they work [here](https://docs.cipherinspector.com/widgets/all). Widgets are extremely versatile. They can:
- Relocate
- Resize
- Go into full-screen mode
- Be configured with settings for each widget type
- Have the same widget added multiple times with different configurations
- Be configured to only analyze specific ciphertexts

Below are a few examples.

#### Frequency Analysis

<img width="50%" height="50%" alt="image" src="https://github.com/user-attachments/assets/adaad509-43ca-4046-9a5c-3fec9462e16b" />
<br/>

#### Index of Coincidence

<img width="50%" height="50%" alt="image" src="https://github.com/user-attachments/assets/4f7df098-723f-4bd1-b245-e095327609c1" />

#### ASCII Distribution

<img width="50%" height="50%" alt="image" src="https://github.com/user-attachments/assets/0fad9ef5-b8c3-4716-954d-03055973003f" />

#### Shannon Entropy

<img width="50%" height="50%" alt="image" src="https://github.com/user-attachments/assets/9e165d68-ee35-4db1-b48d-47f3adcf0f40" />

#### Formatting Widget: Title

The title can be used to organize your dashboard into sections.

<img width="50%" height="50%" alt="image" src="https://github.com/user-attachments/assets/9c83807a-3a69-4a12-b3bb-11addb328c8d" />

### Docs

Ever wonder how any of these widgets work? Our [docs](docs.cipherinspector.com) outline every widget and feature, with a step-by-step explanation on how it works.

### Quality of life

There are many features that will make life easier for cryptanalysts which compliment the core dashboard experience.
- Full Screen mode: In the dashboard, you can hide the sidebar to view a wider dashboard experience.
- Dashboard information: view when a dashboard was created, who created it, and when it was last updated.
- Ciphertext filtering: Widgets can display a subset of ciphers in the dashboard for precise comparisons.
- Widget reuse: Dashboards support adding the same widget multiple times.
- Relocation collision detection: Widgets can move around one another to make relocating widgets easier.
- Right click to save image: Graph widgets can be saved as images.
- Hover on graphs: Hovering on a graph will show you the value(s) plotted at that position.
- Widget full screen: View widgets in a full screen mode to get a better view.
- Widget categories: Widgets now have a category associated with them. The widget library allows you to select categories for easy filtering.
- Widget search: Use the search feature to quickly find the widget you are looking for.
- Light and dark mode: Toggle to your liking!
- Automatic ciphertext colors: Ciphertexts will have colors automatically assigned to distinguish them. You can customize the color of any ciphertext whenever you want.
- Bitstream-based ciphertexts: Cipher inspector asks you to provide the character encoding for the ciphertext and stores the cipher as raw bytes for enhanced analysis techniques.
- Nicknames: Leveraging ciphertext nicknames makes it a lot easier to identify which cipher you are looking at in a widget.

### Enigma Features

Additional convenience features available for a low price:
- Dashboards hub: search, sort, and filter your dashboards for easier access.
- Dashboard customization: Dashboard name, description, and public/private status can be modified at any time.
- Copy dashboards from the playground or public dashboards to your profile for customization.
- Create public or private dashboards and save them to your account.
- Bookmark your ciphertexts for access from any dashboard.

## Reporting bugs or feature requests

> [!TIP]
> Found an issue? Want to see something added? [Create an issue](https://github.com/Cipher-Inspector/.github/issues/new).

## Developer notes

CipherInspector is a full application and costs money to run. Therefore, cipher inspector is offered in Basic (free) and Enigma tiers. The free tier will be a limited experience that will not include the "Enigma" tier functionality.
Enigma tier is focused on covering the cost of operational expenses. A lot of work goes into making this service as useful as possible, so any support you can provide is greatly appreciated!

#### Data retention

While your account is still active, all data is retained. Upon deleting your profile, all of your data will be deleted with it. CipherInspector does not sell your data to third parties. Google and Discord integration are for OAuth only.
