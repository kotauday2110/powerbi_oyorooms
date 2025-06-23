# OYO Rooms Revenue Analytics Dashboard

A comprehensive Power BI dashboard analyzing OYO's hotel booking revenue, occupancy rates, and performance metrics across different property categories and locations in India.

##  Project Overview

This Power BI project provides in-depth analysis of OYO Rooms' business performance, tracking key hospitality metrics including revenue trends, occupancy rates, booking patterns, and property performance across Business and Luxury categories in major Indian cities like Delhi and Mumbai.

##  Key Business Insights

- **Total Revenue**: ₹1.71 billion with 57.87% occupancy rate
- **RevPAR (Revenue Per Available Room)**: ₹7.35K
- **ADR (Average Daily Rate)**: ₹12.70K  
- **Portfolio Coverage**: Properties across Delhi, Mumbai analyzing Business vs Luxury segments
- **Realization Rate**: 24.83% overall performance

##  Dashboard Features

### 1. Revenue Trend Analysis
- Weekly revenue tracking by property category (Business vs Luxury)
- Seasonal performance patterns showing peak revenue periods
- Week-over-week revenue comparison with trend indicators

### 2. Key Performance Indicators (KPIs)
- **Revenue Metrics**: Total revenue, DSRN, ADR, Realization %
- **Occupancy Analytics**: Room utilization rates and booking patterns
- **Performance Indicators**: RevPAR analysis with comparative benchmarks

### 3. Property Performance Dashboard
- City-wise revenue breakdown (Delhi, Mumbai)
- Property-level performance metrics including:
  - Total Revenue per property
  - Occupancy percentage
  - Realization rates
  - Average Daily Rate (ADR)
  - DURN and DBRN metrics

### 4. Interactive Filtering
- **City Filter**: Delhi, Mumbai, All cities
- **Category Filter**: Business, Luxury, All categories  
- **Time Period**: Weekly analysis from W19 to W32
- **Date Range**: Flexible date selection (May-July 2022)

## 🔧 Technical Implementation

### Data Model Structure
- **dim_rooms**: Room dimension table with property details
- **fact_bookings**: Booking transactions with dates and status
- **fact_aggregated_bookings**: Pre-aggregated booking metrics

### Key DAX Measures
The project includes 26+ custom DAX measures for comprehensive analysis:

1. **Total Revenue**: Sum of realized revenue from successful bookings
2. **Total Capacity**: Available room inventory analysis
3. **Total Successful Bookings**: Confirmed reservation count
4. **Occupancy %**: Room utilization rate calculation
5. **Average Rating**: Customer satisfaction metrics
6. **DSRN**: Daily Sellable Room Nights
7. **ADR**: Average Daily Rate calculation
8. **Realisation %**: Revenue realization percentage
9. **RevPAR**: Revenue Per Available Room
10. **DBRN**: Daily Booked Room Nights
11. **DURN**: Daily Utilized Room Nights
12. **Week-over-Week Changes**: Trend analysis measures
13. **Platform-wise Booking Analysis**: Channel performance metrics

### Advanced Analytics Features
- **Booking Platform Analysis**: Performance by booking channels
- **Room Class Segmentation**: Standard, Elite, Premium analysis
- **Cancellation Analytics**: Booking cancellation pattern analysis
- **No-show Rate Tracking**: Customer behavior insights

## 📊 Visualization Components

### Charts & Graphs
- **Line Charts**: Revenue trends over time by category
- **Donut Charts**: Revenue distribution by Business vs Luxury
- **Combo Charts**: RevPAR, ADR, and Occupancy correlation
- **Data Tables**: Detailed property-wise performance metrics
- **KPI Cards**: High-level metric summaries with trend indicators

### Interactive Elements
- **Slicers**: Multi-select filters for cities, categories, and time periods
- **Cross-filtering**: Dynamic interaction between all visuals
- **Drill-down**: Week-level to day-level analysis capability
- **Tooltips**: Additional context on hover for detailed insights

## 🏨 Business Categories Analyzed

### Business Category Properties
- **Focus**: Cost-effective accommodation solutions
- **Performance**: Consistent revenue stream with stable occupancy
- **Key Markets**: Delhi, Mumbai metropolitan areas

### Luxury Category Properties  
- **Focus**: Premium hospitality experience
- **Performance**: Higher ADR with selective occupancy patterns
- **Revenue Impact**: Significant contribution to overall revenue despite lower volume

## 🎯 Key Performance Metrics

| Metric | Value | Description |
|--------|--------|-------------|
| **Total Revenue** | ₹1.71bn | Aggregate revenue across all properties |
| **Occupancy Rate** | 57.87% | Average room utilization rate |
| **RevPAR** | ₹7.35K | Revenue per available room |
| **ADR** | ₹12.70K | Average daily rate achieved |
| **Realization %** | 24.83% | Revenue realization efficiency |

## 📱 Dashboard Navigation

### Page 1: Revenue Trend Analysis
- Weekly revenue performance by category
- Trend analysis with seasonal patterns
- Comparative analysis between Business and Luxury segments

### Page 2: Comprehensive Performance Dashboard  
- Multi-dimensional KPI overview
- Property-wise detailed performance table
- Interactive filtering and cross-analysis capabilities

## 🛠️ Technical Requirements

### Software Requirements
- **Microsoft Power BI Desktop** (latest version)
- **Power BI Pro/Premium** license for sharing and collaboration
- **Excel** for data source management

### Data Sources
- **Booking System**: Transaction data from OYO's booking platform
- **Property Management**: Room inventory and capacity data
- **Customer Database**: Guest information and ratings
- **Revenue System**: Financial transaction records


##  Business Intelligence Features

### Advanced Analytics
- **Trend Analysis**: Week-over-week performance tracking
- **Seasonal Patterns**: Revenue seasonality identification
- **Booking Behavior**: Customer booking pattern analysis
- **Market Segmentation**: Business vs Luxury performance comparison

### Predictive Insights
- **Revenue Forecasting**: Based on historical trends
- **Occupancy Prediction**: Seasonal demand patterns
- **Performance Benchmarking**: Property comparison metrics

## 🏆 Key Achievements

- **Comprehensive Revenue Tracking**: End-to-end revenue analysis across all properties
- **Multi-dimensional Analysis**: City, category, and time-based performance insights
- **Interactive Dashboard**: User-friendly interface with dynamic filtering
- **Scalable Architecture**: Easily expandable for additional properties and metrics
- **Real-time Insights**: Up-to-date business performance monitoring
