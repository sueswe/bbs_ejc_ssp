<html>
<style>

body {
  background-color: #179A0E; 
  font-family: Verdana;
  }

h1 {
  color: white;
  }

</style>
</html>



# Ein Kundenportal für STP-Koordinatoren 

# oder Keyuser im Rahmen der 

# STP-Batchverarbeitungen (TEV)




## Was versteht man unter Batchverarbeitung?

Basierend auf der Graphentheorie, dazu ein wenig 
Theriie =)

Definition: "gerichtete, unterschiedlich gewichtete Graphen"

<html>
<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js">
</script>

<div class="mermaid">
graph TD 
A[Job 1] --> B[Job 2] 
B --> C[Job 3] 
B --> D[Job 4]
D --> E[Job 5]
C --> E
</div>
</html>


<html>
<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js">
</script>
Verboten im Jobablauf:
<div class="mermaid">
graph TD 
A[Job 1] --> B[Job 2] 
B --> C[Job 3] 
B --> D[Job 4]
D --> E[Job 5]
C --> E
C --Circular Dependency --> B
</div>
</html>



***



## Motivation

* Warum baut man Software um ein Stück Enterprise Software herum?

## Entstehungsprozess

* Kundenbefragung: 
