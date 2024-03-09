
Troubleshooting:

Caso haja algum problema para executar os scripts de ativação do ambiente virtual (venv) através no Windows através do VS Code/Powershell:

altere a política padrão de execuçao de Scripts. Por exemplo:

1. Salve as alterações no código.
2. Encerre o VS Code.
3. Abra o VS code novamente como administrador;
4. Execute o comando: Set-ExecutionPolicy -ExecutionPolicy Unrestricted
5. Tente ativar o ambiente virtual novamente com o comando: venv/scripts/activate

Saiba mais sobre políticas de execução de scripts no PS: https://learn.microsoft.com/pt-br/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.4
