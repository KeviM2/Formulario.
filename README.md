# Formulario.
El código define una aplicación JavaFX que muestra una ventana titulada "AllControls" con varios controles de interfaz gráfica organizados en una cuadrícula (GridPane). Incluye botones, casillas de verificación, hipervínculos, botones de alternancia, botones de opción, etiquetas, campos de texto, áreas de texto, barras de progreso, indicadores de progreso y deslizadores. La clase Botones extiende Application, y en el método start, se configura y muestra la interfaz gráfica cuando se inicia la aplicación.

# Codigo.
public class Botones extends Application {

    public static void main(String[] args) {
        launch(args);
    }

    @Override
    public void start(Stage primaryStage) {
        primaryStage.setTitle("AllControls");

        GridPane grid = new GridPane();
        grid.setHgap(10);
        grid.setVgap(10);

        Label label1 = new Label("Button:");
        Button button = new Button("Button");
        
        Label label2 = new Label("Checkbox:");
        CheckBox checkBox = new CheckBox("CheckBox");
        
        Label label3 = new Label("Hyperlink:");
        Hyperlink hyperlink = new Hyperlink("Hyperlink");
        
        Label label4 = new Label("ToggleButton:");
        ToggleButton toggleButton = new ToggleButton("ToggleButton");
        
        Label label5 = new Label("RadioButton:");
        RadioButton radioButton = new RadioButton("RadioButton");
        
        Label label6 = new Label("Label");
        Label label = new Label("Label");
        
        Label label7 = new Label("TextField:");
        TextField textfield = new TextField();

        Label label8 = new Label("PasswordField:");
        PasswordField passwordField = new PasswordField();

        Label label9 = new Label("TextArea:");
        TextArea textArea = new TextArea();

        Label label10 = new Label("ProgressIndicator:");
        ProgressIndicator progressIndicator = new ProgressIndicator();
        
        Label label11 = new Label("ProgressBar");     
        ProgressBar progressBar = new ProgressBar();
        
        Label label12 = new Label("Slider:");
        Slider slider = new Slider();

        grid.add(label1, 0, 0);
        grid.add(button, 1, 0);
        grid.add(label2, 0, 1);
        grid.add(checkBox, 1, 1);
        grid.add(label3, 0, 2);
        grid.add(hyperlink, 1, 2);
        grid.add(label4, 0, 3);
        grid.add(toggleButton, 1, 3);
        grid.add(label5, 0, 4);
        grid.add(radioButton, 1, 4);
        grid.add(label6, 0, 5);
        grid.add(label, 1, 5);
        grid.add(label7, 0, 6);
        grid.add(textfield, 1, 6);
        grid.add(label8, 0, 7);
        grid.add(passwordField, 1, 7);
        grid.add(label9, 0, 8);
        grid.add(textArea, 1, 8);
        grid.add(label10, 0, 9);
        grid.add(progressIndicator, 1, 9);
        grid.add(label11, 0, 10);
        grid.add(progressBar, 1, 10);
        grid.add(label12, 0, 11);
        grid.add(slider, 1, 11);

        Scene scene = new Scene(grid, 400, 400);
        primaryStage.setScene(scene);
        primaryStage.show();
    }
}

# Captura de la Ejecucion.
<img width="443" alt="formulario" src="https://github.com/KeviM2/Formulario./assets/168137294/ba759975-7fd5-43ce-9d78-5ca516250276">
