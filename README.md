1. pierwsza zmiana dotyczyla zastapienia napisu
-    Welcome to Avalonia!
+    <TextBlock Text="okno agenta" HorizontalAlignment="Center" VerticalAlignment="Center"/>
2. druga zmiana powiekszyla dodany tekst
-    <TextBlock Text="okno agenta" HorizontalAlignment="Center" VerticalAlignment="Center"/>
+    <TextBlock Text="okno agenta" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="32"/>
3. trzecia zmiana zmienila czcionke i kolor napisu
-    <TextBlock Text="okno agenta" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="32"/>
+    <TextBlock Text="okno agenta" 
               HorizontalAlignment="Center" 
               VerticalAlignment="Center" 
               FontSize="32" 
               FontFamily="Century Gothic" 
               FontWeight="SemiBold" 
               Foreground="#4F46E5"/>
4. czwarta zmiana zmienila tytul w pasku tytulu
-    Title="okno">
+    Title="Okno agenta">
5. piata zmiana zmienila rozmiar okna na mniejszy
-    mc:Ignorable="d" d:DesignWidth="800" d:DesignHeight="450"
+    mc:Ignorable="d" d:DesignWidth="400" d:DesignHeight="250"
   Width="400" Height="250"
6. szosta zmiana pogrubila litery tekstu
-    FontWeight="SemiBold" 
+    FontWeight="Bold"
7. siodma zmiana dodala pochylenie czcionki
+    FontStyle="Italic"
8. osma zmiana dodala napis opisujacy zadanie
-    TextBlock Text="okno agenta" 
               HorizontalAlignment="Center" 
               VerticalAlignment="Center" 
               FontSize="32" 
               FontFamily="Century Gothic" 
               FontWeight="Bold" 
               Foreground="#4F46E5"/>
+    <StackPanel HorizontalAlignment="Center" 
                VerticalAlignment="Center"
                Spacing="8">
        <TextBlock Text="okno agenta" 
                   HorizontalAlignment="Center" 
                   FontSize="32" 
                   FontFamily="Century Gothic" 
                   FontWeight="Bold" 
                   Foreground="#4F46E5"/>
        <TextBlock Text="agent sam robi okno" 
                   HorizontalAlignment="Center"/>
    </StackPanel>
9. dziewiata zmiana dotyczyla zmiany koloru najnowszego tekstu
-    HorizontalAlignment="Center"/>
+    HorizontalAlignment="Center"
   Foreground="#6B7280"/>
10. dziesiata zmiana zmienila rozmiar i czcionke
+     FontFamily="Century Gothic"
      FontSize="14"
11. jedenasta zmiana dodala kolor tla
-     Title="Okno agenta">
+     Title="Okno agenta"
      Background="#E0E7FF">
12. dwunasta zmiana urozmaicila tlo
+     <Panel>
        <!-- Subtelne tło geometryczne -->
        <Ellipse Width="140" Height="140"
                 Fill="#C7D2FE"
                 Opacity="0.5"
                 HorizontalAlignment="Left"
                 VerticalAlignment="Top"
                 Margin="-30,-30,0,0"/>
        <Ellipse Width="100" Height="100"
                 Fill="#A5B4FC"
                 Opacity="0.4"
                 HorizontalAlignment="Right"
                 VerticalAlignment="Bottom"
                 Margin="0,0,-20,-20"/>

              <Rectangle Width="36" Height="3" 
                       Fill="#818CF8" 
                       RadiusX="1.5" RadiusY="1.5" 
                       HorizontalAlignment="Center"/>
      </Panel>
13. trzynasta zmiana dodala kolejny tekst - opinie agenta
+     <TextBlock Text="Świetne zadanie – taka praca nad oknem to czysta przyjemność!" 
      HorizontalAlignment="Center"/>
14. czternasta zmiana dostosowala rozmiar okna pod dodany w poprzednim punkcie tekst
-     mc:Ignorable="d" d:DesignWidth="400" d:DesignHeight="250"
      Width="400" Height="250"
+     mc:Ignorable="d" d:DesignWidth="460" d:DesignHeight="260"
      Width="460" Height="260"
15. pietnasta zmiana zmienila czcionke i kolor ostatniego tekstu
-     HorizontalAlignment="Center"/>
+     HorizontalAlignment="Center"
      FontFamily="Century Gothic"
      FontSize="13"
      FontStyle="Italic"
      Foreground="#4338CA"/>
16. szesnasta zmiana dodala mala plakietke od agenta z napisem "zadanie ukonczone"
 +    WindowStartupLocation="CenterScreen"
      <!-- Mała plakietka od agenta -->
            <Border Background="#C7D2FE" 
                    CornerRadius="12" 
                    Padding="10,4" 
                    HorizontalAlignment="Center"
                    Margin="0,0,0,4">
                <StackPanel Orientation="Horizontal" Spacing="6" VerticalAlignment="Center">
                    <Ellipse Width="6" Height="6" Fill="#10B981" VerticalAlignment="Center"/>
                    <TextBlock Text="Zadanie ukończone ✨" 
                               FontSize="11" 
                               FontFamily="Century Gothic" 
                               FontWeight="SemiBold" 
                               Foreground="#312E81"/>
                </StackPanel>
            </Border>

 kazdy podpunkt dokladnie analizowalam i wszystkie linijki sa dla mnie zrozumiale
