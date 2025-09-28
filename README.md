# macOS
brew install direnv

# Ubuntu/Debian
sudo apt install direnv

# Habilitar en tu shell (una vez)
echo 'eval "$(direnv hook bash)"' >> ~/.bashrc   # o ~/.zshrc
source ~/.bashrc

# No mostrar configuracion
Create configuration file if it does not exist ~/.config/direnv/direnv.toml
Add log_filter="^$" to configuration
[global]
log_filter="^$"
