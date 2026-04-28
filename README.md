# Ciencia-datos-curso

Este es el primer acercamiento a git

brew update
brew install pyenv
brew install pyenv-virtualenv  # opcional, para gestionar entornos

# Configura tu shell (zsh)
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.zshrc  # si instalaste pyenv-virtualenv
exec "$SHELL"

# Instala y selecciona una versión de Python
pyenv install 3.11.9
pyenv global 3.11.9           # versión por defecto a nivel de usuario

# Dentro del repositorio del curso (local a la carpeta)
pyenv local 3.11.9
python -V

brew install uv
