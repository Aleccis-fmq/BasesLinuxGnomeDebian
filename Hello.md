# Procedimiento de instalacion para Debian Linux 
## MODIFICACION DE PANTALLA
### textos

* Modificacion de tamano de pantalla

~~~sh
@Id
	@GeneratedValue(strategy = GenerationType.IDENTITY)
	private Integer idConsulta;
	 
	
	//muchas consultas a 1 paciente
	@ManyToOne
	@JoinColumn(name = "id_pacientee",nullable = false, foreignKey = @ForeignKey (name = "Fk_consulta_paciente"))
	private Paciente paciente

~~~

```java
@Id
	@GeneratedValue(strategy = GenerationType.IDENTITY)
	private Integer idConsulta;
	 
	
	//muchas consultas a 1 paciente
	@ManyToOne
	@JoinColumn(name = "id_pacientee",nullable = false, foreignKey = @ForeignKey (name = "Fk_consulta_paciente"))
	private Paciente paciente
```

```py
@Id
	@GeneratedValue(strategy = GenerationType.IDENTITY)
	private Integer idConsulta;
	 
	
	//muchas consultas a 1 paciente
	@ManyToOne
	@JoinColumn(name = "id_pacientee",nullable = false, foreignKey = @ForeignKey (name = "Fk_consulta_paciente"))
	private Paciente paciente
```
//

<a href="https://www.youtube.com/watch?v=QdnVT22LBBs
" target="_blank"><img src="https://i.pinimg.com/564x/01/c7/ad/01c7adf5d4b6e6c77b5a30ad02815ea4.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


* [x] Task 1

:fire:

@Alccs
