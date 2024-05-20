program JuegoDeFichas;
var
  rojas, azules, amarillas: integer;
  puntaje: integer;

begin
  // Andrés llegó 3 veces en primer lugar
  rojas := 3;
  azules := 6; // doble cantidad de fichas azules
  amarillas := 0; // no hay fichas amarillas en primer lugar

  // Andrés llegó 4 veces de último lugar
  azules := azules + 4;

  // Andrés llegó 6 veces de intermedio
  azules := azules + 6;

  // Calcular puntaje
  puntaje := rojas + azules - (amarillas * amarillas);

  writeln('El puntaje de Andrés es: ', puntaje);

end.
