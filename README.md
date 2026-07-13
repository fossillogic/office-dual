# **Office Dual**

Office Duel is a fast-paced command-line party game written in C that transforms the classic Rock, Paper, Scissors formula into an office-themed showdown. Players wield everyday office supplies—from rocks, paper, and scissors to staplers, coffee mugs, pencils, tape, and clipboards—each with unique strengths and weaknesses in strategic duels. Featuring single-player matches against adaptive AI, local multiplayer for two to four players, interactive menus, multiple game modes, weapon guides, and match statistics, Office Duel delivers a lightweight, cross-platform experience that’s easy to learn, quick to play, and perfect for friendly competition in the terminal.

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/office_dual.git
    cd office
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run the Project**:

    ```sh
    office
    ```

## **Contributing**

Interested in contributing? Please open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/office_dual).

## **Feedback and Support**

For issues, questions, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/office_dual/issues).

## **License**

This project is licensed under the [Apache 2.0 License](LICENSE).
