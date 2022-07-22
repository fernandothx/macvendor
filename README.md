
# macvendor
Obtenha o fornecedor de um endereço mac no terminal.
```
# sudo mkdir /opt/macvendor 
# sudo chown $USER /opt/macvendor -R 
# wget https://gitlab.com/wireshark/wireshark/-/raw/master/manuf -O /opt/macvendor/macvendor.db
# wget https://raw.githubusercontent.com/remontti/macvendor/main/macvendor -O /opt/macvendor/macvendor
# chmod +x /opt/macvendor/macvendor
# sudo ln -s /opt/macvendor/macvendor /bin/macvendor
# sudo chown $USER /bin/macvendor
# 
```
### Uso
```
# macvendor 'Endereço MAC'
# macvendor -a 'Endereço MAC' (Padrão)
# macvendor -s 'Endereço MAC'
```
<hr>

# macvendor_v2 (outro)
Obtenha o fornecedor de um endereço mac no terminal. (DB ieee-data)

```
# sudo apt install ieee-data
# sudo wget https://raw.githubusercontent.com/remontti/macvendor/main/macvendor_v1 -O /bin/macvendor_v2
# sudo chmod +x /bin/macvendor_v2
```

### Uso
```
# macvendor_v2 'ENDEREÇO MAC'
# macvendor_v2 -a 'ENDEREÇO MAC' (Padrão)
# macvendor_v2 -s 'ENDEREÇO MAC'
```
