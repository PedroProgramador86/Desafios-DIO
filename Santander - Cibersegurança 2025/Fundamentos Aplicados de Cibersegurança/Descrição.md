
O desafio tem o proposito de implementar, documentar e compartilhar um projeto prático utilizando Kali Linux e a ferramenta Medusa, em um ambiente vulnerável (Metasploitable 2), para simular cenários de ataque de força bruta e exercitar medidas de prevenção.

As configurações do ambiente contém:

- Duas VMs (Kali Linux e Metasploitable 2) no VirtualBox, as conexões configuradas em "Modo Bridge" (Pois não consegui implementar o "host-only" nas minhas maquinas virtuais).
- Os ataques serão simulados com força bruta em FTP, automação de tentativas em formulário web (DVWA) e password spraying em SMB com enumeração de usuários.
- A documentação dos testes aplicados, serão feitos em wordlists simples, explicação dos comandos utilizados, validação de acessos e recomendações de mitigação.

> Todos os 3 desafios estão divididos em arquivos diferentes