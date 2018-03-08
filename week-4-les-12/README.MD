# Week 4 - les 12

## Personenlijst klassendiagram
Gegeven onderstaande drie klassen, maak een klassendiagram van deze code.

```java
public class Persoon {
	protected String naam, voornaam;

	public Persoon(String naam, String voornaam) {
		this.naam = naam;
		this.voornaam = voornaam;
	}

	public String getNaam() {
		return naam;
	}

	public void setNaam(String naam) {
		this.naam = naam;
	}

	public String getVoornaam() {
		return voornaam;
	}

	public void setVoornaam(String voornaam) {
		this.voornaam = voornaam;
	}
}

public class Docent extends Persoon {
	protected String code;
	
	public Docent(String naam, String voornaam, String code) {
		super(naam, voornaam);
		this.code = code;
	}

	public String getCode() {
		return code;
	}

	public void setCode(String code) {
		this.code = code;
	}
}

public class Student extends Persoon {
	protected int nummer;
	protected Docent SLBer;
	
	public Student(String naam, String voornaam, int nummer, Docent SLBer) {
		super(naam, voornaam);
		this.nummer = nummer;
		this.SLBer = SLBer;
	}

	public int getNummer() {
		return nummer;
	}

	public void setNummer(int nummer) {
		this.nummer = nummer;
	}

	public Persoon getSLBer() {
		return SLBer;
	}

	public void setSLBer(Docent sLBer) {
		SLBer = sLBer;
	}
}

```
