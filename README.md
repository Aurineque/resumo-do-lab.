# Segurança e Identidade na Azure

A segurança e a identidade no Azure são gerenciadas principalmente através do **Microsoft Entra ID**, anteriormente conhecido como **Azure Active Directory (Azure AD)**. O Microsoft Entra ID é o serviço de identidade e gerenciamento de acesso da Microsoft para ambientes na nuvem, usado para autenticar e autorizar usuários, dispositivos e aplicativos.

### Principais recursos do Microsoft Entra ID (Azure AD):

1. **Autenticação e Autorização**: Permite que usuários façam login em aplicativos, serviços e dispositivos de forma segura. Suporta métodos como senha, autenticação multifator (MFA), biometria, etc.
   
2. **Identidade Híbrida**: Suporta integração com o Active Directory local, permitindo uma experiência de login unificada para usuários em ambientes híbridos (on-premises e na nuvem).

3. **Single Sign-On (SSO)**: Os usuários podem acessar diversos aplicativos e serviços com uma única credencial, melhorando a experiência do usuário e a segurança.

4. **Autenticação Multifator (MFA)**: Adiciona camadas extras de segurança ao exigir que os usuários confirmem sua identidade por meio de um segundo fator, como um código de um aplicativo ou SMS.

5. **Gerenciamento de Dispositivos**: Suporta o registro de dispositivos para aplicar políticas de conformidade e segurança.

6. **Identity Governance**: Recursos para governança de identidade, incluindo provisionamento/desprovisionamento de usuários e monitoramento de acessos, garantindo que apenas as pessoas certas tenham acesso aos recursos adequados.

7. **Conditional Access**: Permite definir políticas de acesso com base em condições como local, dispositivo e risco, bloqueando ou concedendo acesso dinâmico dependendo da situação.

8. **Identity Protection**: Utiliza machine learning e análise de comportamento para detectar e mitigar automaticamente atividades suspeitas, como tentativas de login incomuns.

9. **Privileged Identity Management (PIM)**: Gerencia o acesso de usuários com privilégios elevados, permitindo acesso apenas temporário a funções administrativas.

10. **Azure AD B2C**: Uma solução para gerenciar identidades de consumidores, permitindo que empresas configurem portais de login para seus clientes com base em várias fontes de identidade (redes sociais, emails, etc.).

### Integração com outras soluções de segurança:

O Microsoft Entra ID está intimamente integrado a outras ferramentas de segurança e gerenciamento do Microsoft Azure, como:

- **Microsoft Defender for Identity**: Ajuda a detectar e investigar ameaças avançadas, comprometimentos de identidade e atividades internas maliciosas em tempo real.
  
- **Azure AD Identity Protection**: Monitora o ambiente de identidade para detectar atividades de risco e propõe ações corretivas automáticas ou manuais.

Esse sistema facilita a implementação de uma estratégia de **Zero Trust**, onde todos os acessos são verificados independentemente da localização, oferecendo um controle granular sobre os recursos.
