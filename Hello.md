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

* [x] Task 1

:fire:

@Alccs
