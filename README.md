# Uebung_02_1410653052

public class Sauugetier 
{
    Sauugetier(){ }
    private String name;
    private int alter;
    private String geschlecht;

    public Sauugetier(String name, int alter, String geschlecht) 
    {
        this.name = name;
        this.alter = alter;
        this.geschlecht = geschlecht;
    }

    public String getName() {
        return name;
    }

    public int getAlter() {
        return alter;
    }

    public String getGeschlecht() {
        return geschlecht;
    }

    public void setName(String name) {
        this.name = name;
    }

    public void setAlter(int alter) {
        this.alter = alter;
    }

    public void setGeschlecht(String geschlecht) {
        this.geschlecht = geschlecht;
    }
    
    
    public String printAll()
    {
        return (getName()+"#"+getAlter()+"#"+getGeschlecht());
        
    }
    
}
