#CLASS Transition
public class Transition {
    private String formState;
    private String symbol;
    private String toState;

    public Transition(String formState, String symbol, String toState){
        this.formState = formState;
        this.symbol = symbol;
        this.toState = toState;
    }

    public String getFormState(){
        return formState;
    }

    public String getSymbol(){
        return symbol;
    }

    public String getToState(){
        return toState;
    }

    //Представяне на прехода като текст
    public String toString(){
        return formState+"-"+symbol+">"+toState;
    }
}
