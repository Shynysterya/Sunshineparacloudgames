# Sunshine Para cloudgames
Versão 0.20.0


Salve sou shyn e irei atualiza-los sempre com os lançamentos mais recentes do sunshine, não se esqueçam de entrar em nossa comunidade do discord:https://discord.gg/spacecloud
       
       ATTS
       

(Windows) A versão do instalador do Windows do Sunshine agora é sempre iniciada pelo Sunshine Service. A inicialização manual do Sunshine.exe a partir dos Arquivos de Programas não é mais suportada. Isso foi necessário para solucionar problemas de segurança causados ​​por usuários não administradores com acesso aos dados de configuração do Sunshine. Se você configurou o Agendador de Tarefas ou outros mecanismos para iniciar o Sunshine automaticamente, remova-os do sistema antes de atualizar.
(Windows) O atalho do Menu Iniciar foi reprojetado para uso com o Sunshine Service. Ele agora inicia o Sunshine em segundo plano (se ainda não estiver em execução) e abre a interface do usuário da Web, evitando a persistente janela do prompt de comando presente nas versões anteriores. O atalho do menu Iniciar agora é o método recomendado para abrir a interface do usuário da Web e iniciar o Sunshine.

(Rede/UPnP) Se o Moonlight Internet Hosting Tool estiver instalado junto com o Sunshine, você deve removê-lo ou atualizar para v5.6 ou posterior para evitar conflitos com o suporte UPnP do Sunshine. Como lembrete, a Ferramenta de Hospedagem de Internet Moonlight não é necessária para transmitir pela Internet com o Sunshine. Em vez disso, simplesmente habilite o UPnP na IU da Web do Sunshine.

(Windows) Se o Steam estiver instalado, o driver Steam Streaming Speakers será instalado automaticamente ao iniciar um stream pela primeira vez. Esse comportamento pode ser desabilitado na guia Áudio/Vídeo da IU da Web. Este driver Steam permite suporte para som surround e silenciar o áudio do host sem exigir nenhuma configuração manual

(Entrada) A opção Tempo limite do botão Voltar foi renomeada como Tempo limite da emulação do botão Guia e foi desativada por padrão para garantir que pressionamentos longos no botão Voltar funcionem por padrão. O comportamento anterior pode ser restaurado definindo o tempo limite de emulação do botão guia para 2000.

(Windows) O nome do serviço SunshineSvc foi alterado para SunshineService para tratar de um falso positivo em MalwareBytes. Se você tiver algum script ou outra lógica em seu sistema que esteja usando o nome do serviço, será necessário atualizá-lo para o novo nome.

(Windows) Para oferecer suporte a novos recursos do instalador, install-service.bat não configura mais o serviço para iniciar automaticamente por padrão. Os usuários que executam install-service.bat manualmente na compilação portátil do Sunshine também devem executar autostart-service.bat para iniciar o Sunshine na inicialização. No entanto, instalar o serviço manualmente dessa forma não é recomendado. Em vez disso, use o instalador do Sunshine, que lida com a instalação e configuração do serviço automaticamente.

