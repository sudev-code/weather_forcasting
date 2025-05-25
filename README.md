# weather_forcasting
package model;

public class WeatherData {
    private String cityName;
    private String description;
    private double temperature;
    private double humidity;

    public WeatherData(String cityName, String description, double temperature, double humidity) {
        this.cityName = cityName;
        this.description = description;
        this.temperature = temperature;
        this.humidity = humidity;
    }

    public String getCityName() {
        return cityName;
    }

    public String getDescription() {
        return description;
    }

    public double getTemperature() {
        return temperature;
    }

    public double getHumidity() {
        return humidity;
    }
}
