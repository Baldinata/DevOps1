# DevOps1

 * 
 */
kkkTama on muutos package vk7 Tama on uusi haara from lalala;

/**
 * @author asennus
 *
 */
abstract class Tyontekija {
	
	  private String nimi; 
	  private String asema; 
	  private double palkka; 
	  
	  Tyontekija(String nimi, String asema, double palkka){
		  this.nimi=nimi;
		  this.asema=asema;
		  this.palkka=palkka;
	  }
	
	  public String toString() {
		  return "Työntekijä: " + nimi +" Asema: " + asema +" Palkka: "+ palkka;
	  }

}

class Johtaja extends Tyontekija{
	private String auto;
	private double bonus;
	
	Johtaja(String auto,double bonus){
		super(nimi, asema, palkka);
		this.auto=auto;
		this.bonus=bonus;
	}
	public String toString() {
		  return "Työntekijä: " + nimi +" Asema: " + asema +" Palkka: "+ palkka 
				  + " Autoetu: "+auto + " Bonus: " + bonus;
	  }
	
	
	
	
	
	
	
	
}
