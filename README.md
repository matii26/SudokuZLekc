<Window x:Class="sudoku.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:sudoku"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid Margin="20">
        <TabControl>
            <TabItem Header="4x4">
                <UniformGrid Rows="5" Columns="4" Margin="10">
                    <Button Content="1" Margin="5" Click="Button_Click" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="2" Margin="5" Click="Button_Click_1" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="3" Margin="5" Click="Button_Click_2" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="4" Margin="5" Click="Button_Click_3" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="5" Margin="5" Click="Button_Click_4" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="6" Margin="5" Click="Button_Click_5" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="7" Margin="5" Click="Button_Click_6" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="8" Margin="5" Click="Button_Click_7" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="9" Margin="5" Click="Button_Click_8" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="10" Margin="5" Click="Button_Click_9" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="11" Margin="5" Click="Button_Click_10" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="12" Margin="5" Click="Button_Click_11" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="13" Margin="5" Click="Button_Click_12" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="14" Margin="5" Click="Button_Click_13" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="15" Margin="5" Click="Button_Click_14" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="16" Margin="5" Click="Button_Click_15" Style="{StaticResource SudokuButtonStyle}"/>
                    <Button Content="Sprawdź" Margin="5" Click="CheckButton_Click" Style="{StaticResource CheckButtonStyle}"/>
                </UniformGrid>
            </TabItem>
        </TabControl>
    </Grid>
</Window>


<Window.Resources>
    <Style x:Key="SudokuButtonStyle" TargetType="Button">
        <Setter Property="Width" Value="50"/>
        <Setter Property="Height" Value="50"/>
        <Setter Property="FontSize" Value="20"/>
    </Style>
    <Style x:Key="CheckButtonStyle" TargetType="Button">
        <Setter Property="Width" Value="100"/>
        <Setter Property="Height" Value="50"/>
        <Setter Property="FontSize" Value="20"/>
        <Setter Property="Background" Value="#FF4CAF50"/>
        <Setter Property="Foreground" Value="White"/>
        <Setter Property="BorderThickness" Value="2"/>
        <Setter Property="BorderBrush" Value="#FF388E3C"/>
        <Setter Property="HorizontalAlignment" Value="Center"/>
        <Setter Property="VerticalAlignment" Value="Center"/>
    </Style>
</Window.Resources>
