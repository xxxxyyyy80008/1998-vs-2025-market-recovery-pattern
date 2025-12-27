# Create export function
def export_visualizations():
    viz_names = [
        'visualization_1_price_comparison',
        'visualization_2_normalized',
        'visualization_3_dual_timeline',
        'visualization_4_statistical',
        'visualization_5_daily_returns',
        'visualization_6_cumulative_returns',
        'visualization_7_moving_averages',
        'visualization_8_dashboard'
    ]
    
    for i, name in enumerate(viz_names, 1):
        # Assuming figures stored in fig1, fig2, etc.
        fig = globals()[f'fig{i}']
        fig.savefig(f'../images/{name}.png', 
                   dpi=300, bbox_inches='tight', facecolor='white')
