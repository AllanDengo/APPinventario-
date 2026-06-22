# Política de Segurança

## Visão Geral

O Sistema de Gestão de Inventário Inteligente foi desenvolvido com foco em segurança, rastreabilidade e integridade das informações de estoque.

## Controle de Acesso

- Autenticação obrigatória por usuário e senha.
- Perfis segregados:
  - Administrador
  - Gestor
  - Auditor
  - Operador
- Acesso baseado em permissões.

## Política de Senhas

- Mínimo de 8 caracteres.
- Letras maiúsculas e minúsculas.
- Pelo menos um número.
- Pelo menos um caractere especial.
- Bloqueio após 5 tentativas inválidas.

## Autenticação Multifator

Administradores deverão utilizar autenticação multifator (MFA).

## Proteção dos Dados

- Comunicação criptografada via HTTPS/TLS.
- Dados sensíveis protegidos por criptografia.
- Chaves e segredos armazenados fora do código-fonte.

## Auditoria

Todas as ações realizadas no sistema são registradas:

- Usuário
- Data e hora
- Endereço IP
- Operação executada
- Alterações realizadas

Os registros de auditoria não podem ser removidos.

## Inventário e Divergências

- Divergências geram recontagem automática.
- Recontagens são realizadas de forma cega.
- Divergências críticas exigem validação de gestor ou auditor.

## Backup

- Backup diário automatizado.
- Retenção mínima de 90 dias.
- Testes periódicos de restauração.

## Reportando Vulnerabilidades

Caso identifique uma vulnerabilidade de segurança, abra uma Issue privada ou entre em contato com o administrador do sistema.

Solicitamos que vulnerabilidades não sejam divulgadas publicamente antes da correção.

## Versões Suportadas

| Versão | Suporte |
|---------|---------|
| Atual | ✅ |
| Anteriores | ❌ |
