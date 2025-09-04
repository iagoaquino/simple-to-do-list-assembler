# simple-to-do-list-assembler

## Instalation

**Iniciar os submodulos do git que estão presente nessa pasta**
Abra o seu terminal nessa pasta e digite o comando

```bash
    git submodule update --init --recursive
```

Depois disso você deve notar que as pastas backend e frontend agora possuem os arquivos necessarios para a execução dos programas e uma arquivo Dockerfile

**Fazer o docker compose**
Abra o seu terminal nessa pasta e digite o comando

```bash
    docker compose up
```
Depois disso tanto o backend quanto o frontend devem estar rodando e prontos para serem usados.

Para acessar a interface vá para a pagina "http://localhost:5173/" no seu navegador e você ja deve ser capaz de usar a lista de tarefas.

Para mais detalhes sobre cada parte do sistema individualmente você pode acessar os README.md que estão nos repositorios deles:
- Frontend: https://github.com/iagoaquino/simple-to-do-list-frontend
- Backend: https://github.com/iagoaquino/simple-to-do-list-backend

Obs: Durante os testes eu tive problemas com o frontend apesar de tudo executar como esperado quando eu tentava acessar a pagina http://localhost:5173/ o meu navegador dizia que não tinha nada lá. Minhas ultimas atualizações devem ter consertado esse bug mas eu não faço ideia do porque dele acontecer já que quando eu rodava o programa pelo terminal ele funcionava e o Dockerfile estava configurado corretamente.
