# C++ Libraries Repository

This repository serves as a collection of C++ libraries that can be used as submodules for your C++ projects. It is designed to simplify the management and integration of external libraries into your development workflow.

## Features

- Centralized storage for C++ libraries.
- Easy integration using Git submodules.
- Organized structure for efficient library management.

## Usage

### Cloning the Repository with Submodules

To clone this repository along with its submodules, use the following command:

```bash
git clone --recurse-submodules <repository-url>
```

### Adding a New Library as a Submodule

To add a new library to this repository, follow these steps:

1. Navigate to the repository's root directory:
    ```bash
    cd /path/to/this/repository
    ```

2. Add the library as a submodule:
    ```bash
    git submodule add <library-repository-url> <path-to-library>
    ```

3. Commit the changes:
    ```bash
    git commit -m "Added <library-name> as a submodule"
    ```

### Adding STB as a Submodule

To add STB as a submodule, follow these steps:
1. Navigate to the repository's root directory:
    ```bash
    cd /path/to/this/repository
    ```
2. Add the STB library as a submodule:
    ```bash
    git submodule add https://github.com/nurakmaljalil91/stb

    ```
3. Commit the changes:
    ```bash
    git commit -m "Added STB as a submodule"
    ```

### Adding IMGUI as a Submodule
To add IMGUI as a submodule, follow these steps:

1. Navigate to the repository's root directory:
    ```bash
    cd /path/to/this/repository
    ```
2. Add the IMGUI library as a submodule:
    ```bash
    git submodule add https://github.com/nurakmaljalil91/imgui
    ```
3. Commit the changes:
    ```bash
    git commit -m "Added IMGUI as a submodule"
    ```

### Updating Submodules

To update all submodules to their latest versions, run:

```bash
git submodule update --remote
```

## Directory Structure

```
lib/
├── entt/
├── glad/
├── glm/
├── imgui/
├── glm/
├── rapidjson/
├── SDL_image/
├── SDL_mixer/
├── SDL_ttf/
├── SDL2/
├── simdjson/
├── spdlog/
├── stb/
└── tinyobjloader/

```

- Each library is stored in its own directory under the `lib/` folder.

## Libraries Included
- [entt](https://github.com/cpp-utilities/entt)
- [glad](https://github.com/Dav1dde/glad)
- [glm](https://github.com/g-truc/glm)
- [imgui](https://github.com/ocornut/imgui)
- [rapidjson](https://github.com/Tencent/rapidjson)
- [SDL_image](https://github.com/libsdl-org/SDL_image)
- [SDL_mixer](https://github.com/libsdl-org/SDL_mixer)
- [SDL_ttf](https://github.com/libsdl-org/SDL_ttf)
- [SDL2](https://github.com/libsdl-org/SDL)
- [simdjson](https://github.com/simdjson/simdjson)
- [spdlog](https://github.com/gabime/spdlog)
- [stb](https://github.com/nurakmaljalil91/stb)
- [tinyobjloader](https://github.com/tinyobjloader/tinyobjloader)

## Contributing

Contributions are welcome! If you have a library you'd like to add, feel free to open a pull request or submit an issue.

## License

This repository is licensed under the [MIT License](LICENSE). Please ensure that any libraries added comply with their respective licenses.

## Contact

For questions or suggestions, please contact Nur Akmal Jalil at nurakmaljalil91@gmail.com