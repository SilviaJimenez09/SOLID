# SOLID
Aplicacion de principios SOLID
public class Movie {
 
public String getTitle() {
return "The Godfather";
}
 
public String getDirector() {
return "Francis Ford Coppola";
}

public String getDate() {
return "1972";
}

public String getReference() {
return "Novel-Mario Puzo";
}
}

public interface DVD{
 
void playMovie(Movie movie);
}
 
public class DVD implements DVD {
 
public String playMovie(movie) {
System.out.println(movie);
}
}
