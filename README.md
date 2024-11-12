# Desafio de Integração - XML e JSON
Este repositório contém a modelagem de dados em XML e JSON para gerenciamento de pacientes e consultas médicas. 


## Estruturas de Dados

### XML

```xml
  <paciente>  
    <id>1</id>  
    <nome>Olivia Rodrigo</nome>  
    <dataNascimento>2003-02-20</dataNascimento>  
    <sexo>Feminino</sexo>  
    <email>olivia.rodrigo@gmail.com</email>
    <telefone>(11) 91234-5678</telefone>  
      
    <convenio>  
        <id>321</id>  
        <nome>Unimed</nome>  
        <dataInicio>2021-04-01</dataInicio>  
        <dataFim>2025-04-01</dataFim>  
    </convenio>  

</paciente>

<consulta>  
    <id>4400</id>  
    <pacienteId>1</pacienteId>  
    <medicoId>200</medicoId>  
    <dataConsulta>2024-11-22</dataConsulta>  
    <especialidade>Dermatologia</especialidade>  
    <status>Agendada</status>  
    <observacao>Paciente relata coceira e manchas na pele</observacao>  
    <dataRegistro>2024-11-12</dataRegistro>  
</consulta>
```

### JSON

```json
{  
    "paciente": {  
        "id": 1,  
        "nome": "Rogério Pereira",  
        "dataNascimento": "1998-05-02",  
        "sexo": "Masculino",  
        "telefone": "(11) 98765-4321",  
        "email": "rog_pereira33@hotmail.com",  
        "convenio": {  
            "id": 422,  
            "nome": "NotreDame Intermédica",  
            "dataInicio": "2023-04-14",  
            "dataFim": "2027-04-14"  
        }  
    },  
    "consulta": {  
        "id": 4525,  
        "pacienteId": 1,  
        "medicoId": 101,  
        "dataConsulta": "2024-12-02",  
        "especialidade": "Cardiologia",  
        "status": "Agendada",  
        "observacoes": "Exame de rotina",  
        "dataRegistro": "2024-11-12"  
    }  
}
```
