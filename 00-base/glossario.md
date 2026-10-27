# Glossário

## Termos 

### PACS (Picture Archiving and Communication System)
Sistema de arquivamento e comunicação de imagens que armazena exames de imagem e reúne em um só lugar as imagens de diversas modalidades. Assim, o médico acessa, de qualquer lugar autorizado, não apenas as imagens atuais, mas também as anteriores, para comparação.

### RIS (Radiology Information System)
Sistema de informação da radiologia que faz a gestão do setor de imagem. Controla agendamentos, a worklist e o status de cada exame, como se foi realizado ou laudado.

### HIS (Hospital Information System)
Sistema de informação Hospitalar que gerencia as informações de todos os pacientes do hospital, como prontuário, cirurgia, faturamento, cadastro do paciente, internação e agenda geral.

### Worklist
Lista de exames pendentes no setor de imagem, que vai do sistema ao aparelho. Assim que o paciente chega na unidade, e a recepção realiza a abertura da ficha, o cadastro dele já aparece no aparelho, sem a necessidade de digitá-lo manualmente. O que reduz a possibilidade de erro humano, por digitar os dados de forma incorreta.

### Laudo (Radiology Report)
Registro realizado pelo médico especialista para descrever os achados nas imagens e elaborar uma conclusão diagnóstica afim de apoiar o médico solicitante a definir a melhor conduta;

### Modalidade (Modality)
Método ou equipamento utilizado para realizar o exame de imagem. Por exemplo, Raio-X , Mamografia, Tomografia Computadorizada, Ultrassonografia, e etc.

### DICOM (Digital Imaging and Communications in Medicine)
Padrão que define o formato em que as imagens são exportadas, quais dados as acompanham e como são enviados, e que confirma o recebimento (ou não) das imagens no PACS. Essa padronização vale para todas as modalidades do setor de radiologia, independentemente da marca do aparelho. Assim, imagens de modalidades diferentes chegam ao PACS de forma padronizada e ficam reunidas no mesmo sistema.

### AE Title (Application Entity Title)
Nome que identifica cada equipamento ou sistema na comunicação DICOM, como o aparelho e o PACS. Ele é informado quando o aparelho abre a conexão para enviar as imagens, e os dois lados precisam se reconhecer: cada um cadastra o AE Title do outro. Se o nome não for reconhecido, o PACS recusa o envio.

### HL7 (Health Level Seven)
Padrão que define o formato em que as informações de saúde, como cadastro do paciente, pedido de exame, status e resultado, são trocadas entre os diferentes sistemas do hospital. Assim, sistemas como o HIS e o RIS conseguem se comunicar, mesmo sendo de fabricantes diferentes. Enquanto o DICOM padroniza as imagens, o HL7 padroniza as informações que trafegam entre os sistemas.

### VNA (Vendor Neutral Archive)
Sistema de arquivo em que as imagens são guardadas no formato padrão DICOM, o que o torna neutro: o PACS de qualquer fabricante consegue acessá-las. Assim, se o hospital trocar de sistema PACS, continua com acesso a todos os exames anteriores.





