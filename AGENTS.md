# TOTEM

Investigue o mapa em `config/totem.keymap` e os shields em `config/boards/`. Use `build.yaml` como matriz de validação das duas metades e `config/west.yml` como fonte da revisão ZMK; se a ref for móvel, registre o commit resolvido com o resultado.

Verifique artefatos das duas metades no [build do PR](.github/workflows/build.yml). Build não identifica o firmware instalado nem testa o pareamento. Flash e limpeza de associações são operações distintas e exigem autorização e confirmação da metade/perfil. Para diagnosticar Bluetooth, preserve os demais perfis; desconectar não equivale a limpar o pareamento.
